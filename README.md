# 🏛️ University-Carbon-Neutrality-Council-Platform

> **대학 탄소중립 정보공개 플랫폼**은 대학별 에너지 소비와 온실가스 데이터를 투명하게 개방하여, 대학 구성원 중심의 자발적 감축을 실현하는 디지털 대시보드입니다. 기존 행정 시스템의 연 1회 사후 보고식 정보 시차를 극복하고, 전국 대학의 데이터를 1인당·면적당 원단위 지표로 변환해 객관적인 랭킹을 시각화합니다. 나아가 실시간 건물에너지관리시스템(BEMS) 형태의 모니터링을 지향하며, 연도별·월별·건물별 배출량 차트와 함께 커뮤니티, ESG 채용, 교육 콘텐츠를 제공하는 종합적인 기후위기 대응 거점 공간입니다.

---

## 📌 주요 기능
* **원단위 지표 시각화:** 전국 대학의 온실가스 및 전력 사용량을 1인당·면적당 지표로 변환하여 객관적인 랭킹 제공
* **미시적 수요 관리:** 개별 대학의 연도별·월별·건물별·기관별 배출량을 직관적인 차트로 모니터링 (BEMS 지향)
* **종합 거점 공간:** 기후위기 관련 교육 콘텐츠, 보고서 아카이빙, 커뮤니티, ESG 채용 정보 제공

---

## 🗄️ 데이터베이스 스키마 및 명세서 (Data Schema & Specifications)
본 프로젝트의 데이터는 크게 '기본 정보', '규모 지표', '목표 및 이행 지표', '실제 배출/사용량 지표'로 나뉩니다. 

### 1. 대학 기본 정보 (Categorical & Static)
* `university_id` (String, Primary Key): 대학 고유 식별자
* `university_name` (String, Required): 대학교명
* `region` (String, Required): 소재지 (광역지자체 단위 ex. '서울특별시', '부산광역시' 등. '수도권/비수도권'과 같은 이분법적 분리 지양)
* `system_type` (Enum, Required): 탄소관리 제도 포함 여부 `['배출권거래제', '목표관리제', '해당없음']`

### 2. 규모 및 인프라 지표 (Demographic & Physical)
* `year` (Integer, Required): 데이터 측정 연도
* `total_members` (Integer, Required): 총 구성원 수
  * **산출 로직:** `재학생 수` + `전임교원 수` + `직원 수` (기타 근로자 포함 여부는 협의된 기준 적용)
* `campus_gfa_sqm` (Float, Required): 캠퍼스 건축 연면적(㎡)
  * **주의:** 호수나 산 등 자연면적이 포함된 전체 교지면적이 아닌, 실제 냉난방이 이루어지는 '건축 연면적'을 기준으로 하여 데이터 왜곡(모순) 방지.

### 3. 에너지 사용 및 탄소 배출량 (Raw Data)
* `ghg_emissions_tco2eq` (Float, Required): 온실가스 총 배출량 (tCO2eq)
* `energy_usage_tj` (Float, Nullable): 총 에너지 사용량 (TJ)
  * **예외 처리:** 최근 연도 데이터나 에너지 사용량 데이터는 결측치(Null)가 많으므로, 시각화 시 0으로 처리하지 않고 '데이터 없음'으로 렌더링.
* `carbon_credit_purchase_krw` (Float, Nullable): 탄소배출권 구매액 (원)
* `season_or_month` (String, Nullable): 계절별/월별 측정 구분 (데이터 존재 시에만 사용)

### 4. 제도 이행 및 평가 지표 (Compliance Data)
* `has_baseline` (Boolean, Required): 기준배출량 존재 여부 (목표관리제/배출권거래제 대상 여부 필터링 용도)
* `baseline_emissions` (Float, Nullable): 정부 할당/지정 기준배출량
* `net_emissions` (Float, Nullable): 온실가스 순배출량

---

## ⚙️ 파생 변수 및 계산 로직 (Calculated Fields)
백엔드 단에서 Raw Data를 바탕으로 아래의 항목들을 자동 계산하여 프론트엔드로 전달합니다.

**[원단위 지표]** (실질적이고 객관적인 학교 간 비교 목적)
1. `emissions_per_capita` = `ghg_emissions_tco2eq` / `total_members` (1인당 탄소배출량)
2. `energy_per_capita` = `energy_usage_tj` / `total_members` (1인당 에너지사용량)
3. `emissions_per_area` = `ghg_emissions_tco2eq` / `campus_gfa_sqm` (면적당 탄소배출량)
4. `energy_per_area` = `energy_usage_tj` / `campus_gfa_sqm` (면적당 에너지사용량)

**[제도 이행 평가 지표]** (`has_baseline`이 True일 때만 계산)
5. `diff_from_baseline` = `net_emissions` - `baseline_emissions` (기준대비 증감량)
6. `diff_ratio_from_baseline` = (`diff_from_baseline` / `baseline_emissions`) * 100 (기준대비 증감률 %)
7. `excess_emissions` = MAX(0, `diff_from_baseline`) (초과배출량: 양수일 경우만 표기)
8. `reduction_margin` = MAX(0, -`diff_from_baseline`) (감축 여유분: 음수일 경우 절대값으로 표기)
9. `achievement_rate` = (목표 감축량 달성 비율 - 세부 산식 추가 적용)

---

## 📊 UI/UX 데이터 바인딩 가이드 (Data Binding Guide)
프론트엔드 차트 라이브러리(ex. Recharts, Chart.js) 연동 시 아래의 기준을 따릅니다.
* **단일 학교 상세 페이지 (Single University View):** 연도별 변화 추이를 한눈에 볼 수 있도록 **꺾은선 그래프(Line Chart)**로 렌더링. 
  * *대상 컬럼:* 총 사용량, 1인당 배출량, 탄소배출권 구매액 등
* **다중 학교 비교 뷰 (Multiple Universities View):** 타 학교와의 직접적인 스케일 비교 및 경쟁 유도를 위해 **막대그래프(Bar Chart)**로 렌더링. 
  * *대상 컬럼:* 1인당/면적당 사용량, 달성률 등

---

## 🛠️ 기술 스택 (Tech Stack)
* **Frontend:** *(예: React, Next.js, Chart.js 등)*
* **Backend:** *(예: Node.js, Python 등)*
* **Database:** *(예: PostgreSQL, MySQL 등)*
