<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700;800;900&display=swap" rel="stylesheet">
<title>KUCE — 대학 탄소중립 정보공개 플랫폼</title>
<style>
:root{
  --bg-top:#0E2A4E;          /* 짙은 남색 */
  --bg-bot:#0F3D2E;          /* 짙은 초록 */
  --card:#132F52;            /* 카드(짙은 남색) */
  --card-soft:#1A3A60;
  --ink:#F2F6FB;             /* 본문(밝은색) */
  --ink-soft:#9FB4CC;
  --line:#2C4A73;
  --primary:#F5C84B;         /* 포인트: 포스터 노랑 */
  --primary-deep:#E0AE28;
  --primary-pale:#233F66;
  --blue:#5BA4E6;
  --mint:#57C99B;            /* 감소(긍정) */
  --coral:#F08A74;           /* 증가(주의) */
  --gold:#F5C84B;            /* 우리 학교 하이라이트 */
  --gold-pale:rgba(245,200,75,.12);
  --radius:16px;
  --shadow:0 4px 18px rgba(0,0,0,.35);
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  font-family:"Noto Sans KR","Pretendard","Apple SD Gothic Neo","Malgun Gothic",sans-serif;
  background:linear-gradient(160deg,var(--bg-top) 0%,#0D3050 45%,var(--bg-bot) 100%);
  background-attachment:fixed;
  color:var(--ink); line-height:1.55; letter-spacing:-.01em;
}
button{font-family:inherit;cursor:pointer;border:none;background:none;color:inherit}
input{font-family:inherit}

/* ---------- 상단 고정 바 ---------- */
.topbar{
  position:sticky;top:0;z-index:50;
  background:rgba(10,26,48,.85);backdrop-filter:blur(10px);
  border-bottom:1px solid var(--line);
}
.topbar-inner{
  max-width:1080px;margin:0 auto;padding:12px 20px;
  display:flex;align-items:center;gap:16px;
}
.logo{display:flex;align-items:center;gap:9px;font-weight:900;font-size:21px;color:#fff;cursor:pointer;white-space:nowrap;letter-spacing:.02em}
.logo .leaf{width:28px;height:28px;border-radius:9px;background:linear-gradient(135deg,#F5C84B,#E0891F);display:grid;place-items:center;color:#12263F;font-size:16px}
.searchwrap{position:relative;flex:1;max-width:520px}
.searchwrap input{
  width:100%;padding:10px 40px 10px 14px;border:1.5px solid var(--line);
  border-radius:999px;font-size:14px;background:#0E2340;color:var(--ink);outline:none;
  transition:border-color .15s;
}
.searchwrap input::placeholder{color:#6E86A6}
.searchwrap input:focus{border-color:var(--primary)}
.searchwrap .sicon{position:absolute;right:14px;top:50%;transform:translateY(-50%);color:var(--primary);font-size:15px}
.search-drop{
  position:absolute;top:calc(100% + 6px);left:0;right:0;background:#132F52;
  border:1px solid var(--line);border-radius:12px;box-shadow:var(--shadow);
  max-height:280px;overflow:auto;display:none;z-index:60;
}
.search-drop.open{display:block}
.search-drop button{display:flex;justify-content:space-between;width:100%;padding:10px 14px;font-size:14px;text-align:left}
.search-drop button:hover{background:var(--primary-pale)}
.search-drop .rk{color:var(--ink-soft);font-size:12px}
.myschool-chip{
  display:none;align-items:center;gap:6px;background:rgba(245,200,75,.15);
  border:1px solid var(--gold);color:var(--gold);border-radius:999px;
  padding:6px 12px;font-size:13px;font-weight:800;white-space:nowrap;
}
.myschool-chip.on{display:flex}
.myschool-chip .x{cursor:pointer;font-weight:400;opacity:.7}

/* ---------- 인스타그램 버튼 ---------- */
.insta-btn{
  display:inline-flex;align-items:center;gap:6px;
  border:1.5px solid var(--line);border-radius:999px;padding:7px 13px;
  font-size:13px;font-weight:800;color:var(--ink-soft);text-decoration:none;
  white-space:nowrap;transition:.15s;
}
.insta-btn:hover{
  color:#fff;border-color:transparent;
  background:linear-gradient(45deg,#F58529,#DD2A7B 55%,#8134AF);
}
@media(max-width:560px){.insta-btn span{display:none}.insta-btn{padding:7px 9px}}

/* ---------- 공통 레이아웃 ---------- */
.page{max-width:1080px;margin:0 auto;padding:28px 20px 110px;display:none}
.page.active{display:block;animation:fadein .25s ease}
@keyframes fadein{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}
.card{background:var(--card);border:1px solid var(--line);border-radius:var(--radius);box-shadow:var(--shadow)}
.section-title{font-size:17px;font-weight:800;margin-bottom:12px;display:flex;align-items:center;gap:8px;color:#fff}
.muted{color:var(--ink-soft);font-size:13px}
.pill-btn{
  background:var(--primary);color:#12263F;border-radius:999px;padding:12px 24px;
  font-size:15px;font-weight:900;transition:.15s;
}
.pill-btn:hover{background:#FFDD75;transform:translateY(-1px)}
.ghost-btn{
  border:1.5px solid var(--line);border-radius:999px;padding:8px 16px;
  font-size:13px;font-weight:700;color:var(--primary);background:transparent;transition:.15s;
}
.ghost-btn:hover{border-color:var(--primary);background:rgba(245,200,75,.12)}

/* ---------- 홈: 히어로 ---------- */
.hero{
  background:radial-gradient(120% 160% at 85% -20%,rgba(91,164,230,.25),transparent 55%),
             linear-gradient(135deg,#10315B 0%,#0F3D2E 100%);
  border:1px solid var(--line);border-radius:22px;padding:40px 34px;position:relative;overflow:hidden;
}
.hero::after{
  content:"⚡";position:absolute;right:26px;bottom:-14px;font-size:120px;opacity:.08;transform:rotate(-12deg);
}
.hero .eyebrow{font-size:12.5px;font-weight:800;color:var(--primary);letter-spacing:.14em;margin-bottom:10px}
.hero h1{font-size:clamp(26px,4.2vw,42px);font-weight:900;line-height:1.25;color:#fff;letter-spacing:-.02em}
.hero .sum{
  display:inline-flex;align-items:center;gap:10px;margin-top:18px;
  background:var(--primary);border-radius:14px;padding:12px 20px;font-size:15px;font-weight:800;color:#12263F;
}
.hero .sum .delta{font-size:20px;font-weight:900}
.hero .sum .delta.down{color:#0B6B4A}.hero .sum .delta.up{color:#B4432E}
.delta.down{color:var(--mint)} .delta.up{color:var(--coral)}
.hero .updated{margin-top:12px;font-size:12px;color:var(--ink-soft)}

/* ---------- 홈: 전국 카드 ---------- */
.natgrid{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:22px}
@media(max-width:760px){.natgrid{grid-template-columns:1fr}}
.natcard{padding:24px 22px 18px;display:flex;flex-direction:column;gap:6px}
.natcard .head{display:flex;justify-content:space-between;align-items:flex-start}
.natcard .label{font-size:14px;font-weight:800;color:var(--primary)}
.natcard .big{font-size:32px;font-weight:900;letter-spacing:-.02em;color:#fff}
.natcard .big small{font-size:14px;font-weight:600;color:var(--ink-soft);margin-left:4px}
.natcard .chg{font-size:16px;font-weight:800;margin-top:2px}
.minichart{margin-top:14px;height:120px;display:flex;align-items:flex-end;gap:10px}
.minichart .bar{
  flex:1;border-radius:8px 8px 4px 4px;position:relative;
  background:linear-gradient(180deg,#6FB0E8,#3E7DC0);
  min-height:8px;transition:height .5s ease;
}
.minichart .bar.last{background:linear-gradient(180deg,#FFD86B,#E0A428)}
.minichart .bar span{
  position:absolute;bottom:-20px;left:50%;transform:translateX(-50%);
  font-size:11px;color:var(--ink-soft);white-space:nowrap;
}
.minichart-pad{height:22px}

/* ---------- sticky CTA ---------- */
.sticky-cta{
  position:fixed;left:50%;bottom:22px;transform:translateX(-50%);z-index:40;
  background:var(--primary);color:#12263F;border-radius:999px;
  padding:15px 30px;font-size:15px;font-weight:900;
  box-shadow:0 10px 28px rgba(245,200,75,.35);display:flex;gap:8px;align-items:center;
  transition:transform .15s;
}
.sticky-cta:hover{transform:translateX(-50%) scale(1.04)}

/* ---------- 비교 페이지 ---------- */
.tabs{display:flex;gap:6px;border-bottom:2px solid var(--line);margin-bottom:18px}
.tabs button{
  padding:10px 18px;font-size:15px;font-weight:800;color:var(--ink-soft);
  border-bottom:3px solid transparent;margin-bottom:-2px;transition:.15s;
}
.tabs button.on{color:var(--primary);border-color:var(--primary)}
.filterbar{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:10px;margin-bottom:14px}
.chips{display:flex;gap:8px;flex-wrap:wrap}
.chip{
  border:1.5px solid var(--line);background:transparent;border-radius:999px;
  padding:7px 14px;font-size:13px;font-weight:700;color:var(--ink-soft);transition:.15s;
}
.chip.on{background:var(--primary);border-color:var(--primary);color:#12263F}
.rankwrap{padding:18px 18px 12px}
.rankrow{
  display:grid;grid-template-columns:44px 150px 1fr 110px;gap:10px;align-items:center;
  padding:7px 8px;border-radius:10px;cursor:pointer;transition:background .12s;
}
.rankrow:hover{background:var(--primary-pale)}
.rankrow .num{font-weight:800;color:var(--ink-soft);font-size:14px;text-align:center}
.rankrow .name{font-size:14px;font-weight:700;color:#fff;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.rankrow .barcell{background:#0E2544;border-radius:8px;height:22px;overflow:hidden}
.rankrow .barfill{
  height:100%;border-radius:8px;
  background:linear-gradient(90deg,#3E7DC0,#6FB0E8);
  transition:width .6s cubic-bezier(.2,.8,.2,1);
}
.rankrow .val{font-size:13px;font-weight:700;text-align:right;color:var(--ink);white-space:nowrap}
.rankrow.mine{background:rgba(245,200,75,.12);outline:2px solid var(--gold)}
.rankrow.mine .name{color:var(--gold)}
.rankrow.mine .barfill{background:linear-gradient(90deg,#E0A428,#FFD86B)}
.rankrow.mine .name::after{content:" ⚡";font-size:12px}
.rank-note{display:flex;justify-content:space-between;align-items:center;margin-top:10px;flex-wrap:wrap;gap:8px}

/* ---------- 상세 페이지 ---------- */
.detail-head{display:flex;justify-content:space-between;align-items:flex-start;gap:12px;flex-wrap:wrap}
.detail-head h2{font-size:28px;font-weight:900;color:#fff}
.badge-rank{
  display:inline-flex;align-items:center;gap:8px;margin-top:10px;
  background:var(--primary);color:#12263F;
  border-radius:999px;padding:8px 20px;font-size:20px;font-weight:900;
}
.badge-rank small{font-size:13px;font-weight:700;color:#3D5470}
.iconbtn{
  width:42px;height:42px;border-radius:50%;border:1.5px solid var(--line);
  background:var(--card);font-size:17px;display:grid;place-items:center;transition:.15s;
}
.iconbtn:hover{border-color:var(--primary);background:var(--primary-pale)}
.kpigrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:14px;margin:18px 0}
.kpi{padding:16px 18px}
.kpi .k-label{font-size:12.5px;font-weight:800;color:var(--primary)}
.kpi .k-val{font-size:22px;font-weight:900;margin-top:2px;color:#fff}
.kpi .k-val small{font-size:12px;color:var(--ink-soft);font-weight:600;margin-left:3px}
.kpi .k-chg{font-size:13px;font-weight:800;margin-top:2px}
.linechart-card{padding:20px}
.linechart-card svg{width:100%;height:auto;display:block}
.infogrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
.inforow{padding:14px 16px;display:flex;flex-direction:column;gap:2px}
.inforow .il{font-size:12px;font-weight:800;color:var(--primary)}
.inforow .iv{font-size:15px;font-weight:700;color:#fff}
.simgrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px}
.simcard{padding:14px 16px;cursor:pointer;transition:.15s}
.simcard:hover{border-color:var(--primary);transform:translateY(-2px)}
.simcard .sn{font-weight:800;font-size:14px;color:#fff}
.simcard .sv{font-size:12.5px;color:var(--ink-soft);margin-top:4px}
.detail-cta{display:flex;justify-content:center;margin-top:26px}
.toast{
  position:fixed;bottom:90px;left:50%;transform:translateX(-50%);
  background:var(--primary);color:#12263F;padding:10px 20px;border-radius:999px;
  font-size:13.5px;font-weight:700;opacity:0;pointer-events:none;transition:opacity .25s;z-index:70;
}
.toast.show{opacity:1}
.crumb{font-size:13px;color:var(--ink-soft);margin-bottom:14px;display:flex;gap:6px;align-items:center}
.crumb button{color:var(--primary);font-weight:800;font-size:13px}
.crumb button:hover{text-decoration:underline}
.foot{max-width:1080px;margin:0 auto;padding:0 20px 40px;font-size:12px;color:var(--ink-soft)}
@media(max-width:640px){
  .rankrow{grid-template-columns:32px 96px 1fr 84px;gap:6px}
  .rankrow .name{font-size:12.5px}
  .rankrow .val{font-size:11.5px}
  .topbar-inner{flex-wrap:wrap}
}

/* ---------- 상단 내비게이션 ---------- */
.topnav{display:flex;gap:2px}
.topnav button{
  padding:7px 12px;border-radius:999px;font-size:13.5px;font-weight:700;
  color:var(--ink-soft);transition:.15s;white-space:nowrap;
}
.topnav button:hover{color:var(--primary);background:rgba(245,200,75,.1)}

/* ---------- 지도 페이지 ---------- */
.mapgrid{display:grid;grid-template-columns:1.25fr .9fr;gap:18px;align-items:start}
@media(max-width:860px){.mapgrid{grid-template-columns:1fr}}
.mapcard{padding:10px 6px 4px}
.mapcard svg,.mapinset svg{width:100%;height:auto;display:block}
.mapside{display:flex;flex-direction:column;gap:14px}
.mapinset{padding:12px 14px 8px}
.inset-title{font-size:13px;font-weight:800;color:var(--primary);margin-bottom:4px}
.mappanel{min-height:150px}
.mappanel .mp-in{padding:18px}
.mappanel .mp-name{font-size:19px;font-weight:900;color:#fff}
.mappanel .mp-rank{display:inline-block;background:var(--primary);color:#12263F;border-radius:999px;padding:3px 12px;font-size:13px;font-weight:900;margin:8px 0 10px}
.mappanel .mp-stat{font-size:13.5px;color:var(--ink-soft);line-height:1.8}
.mappanel .mp-stat b{color:var(--ink)}
.mapdot{cursor:pointer;transition:r .15s}
.mapdot:hover{filter:brightness(1.25)}
.maplabel{pointer-events:none;font-weight:700}

</style>
</head>
<body>

<!-- 상단 고정 바 -->
<header class="topbar">
  <div class="topbar-inner">
    <div class="logo" onclick="go('home')"><span class="leaf">⚡</span>KUCE</div>
    <nav class="topnav">
      <button onclick="go('compare')">학교 비교</button>
      <button onclick="go('map')">전국 지도</button>
    </nav>
    <div class="searchwrap">
      <input id="searchInput" type="text" placeholder="대학명 검색 — 우리 학교를 찾아보세요" autocomplete="off">
      <span class="sicon">🔍</span>
      <div class="search-drop" id="searchDrop"></div>
    </div>
    <a class="insta-btn" href="https://www.instagram.com/net0campus?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank" rel="noopener" title="대학 탄소중립 학생 협의체 인스타그램">
      <svg viewBox="0 0 24 24" width="16" height="16" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <rect x="2" y="2" width="20" height="20" rx="5"/>
        <circle cx="12" cy="12" r="4.2"/>
        <circle cx="17.4" cy="6.6" r="1.3" fill="currentColor" stroke="none"/>
      </svg><span>@net0campus</span>
    </a>
    <div class="myschool-chip" id="myChip">
      <span id="myChipName"></span><span class="x" onclick="clearMySchool(event)">✕</span>
    </div>
  </div>
</header>

<!-- ================= 홈 ================= -->
<main class="page active" id="page-home">
  <section class="hero">
    <div class="eyebrow">KOREAN UNIVERSITIES FOR CARBON &amp; ENERGY REDUCTION</div>
    <h1>2026 전국 대학 탄소배출 현황</h1>
    <div class="sum">
      전국 대학 탄소배출량, 전년 대비
      <span class="delta down" id="heroDelta">−3.1%</span>
      감소
    </div>
    <div class="updated" id="heroUpdated">데이터 출처: 온실가스종합정보센터·대학알리미 (샘플) · 최근 업데이트 2026.07</div>
  </section>

  <div class="natgrid">
    <div class="card natcard">
      <div class="head">
        <div>
          <div class="label">전국 대학 탄소배출량</div>
          <div class="big" id="natCarbonVal"></div>
          <div class="chg" id="natCarbonChg"></div>
        </div>
        <button class="ghost-btn" onclick="go('compare','carbon')">전체보기</button>
      </div>
      <div class="minichart" id="natCarbonChart"></div>
      <div class="minichart-pad"></div>
    </div>
    <div class="card natcard">
      <div class="head">
        <div>
          <div class="label">전국 대학 에너지사용량</div>
          <div class="big" id="natEnergyVal"></div>
          <div class="chg" id="natEnergyChg"></div>
        </div>
        <button class="ghost-btn" onclick="go('compare','energy')">전체보기</button>
      </div>
      <div class="minichart" id="natEnergyChart"></div>
      <div class="minichart-pad"></div>
    </div>
  </div>
</main>

<!-- ================= 비교 페이지 ================= -->
<main class="page" id="page-compare">
  <div class="crumb"><button onclick="go('home')">홈</button> › 학교 비교 데이터</div>
  <div class="tabs">
    <button id="tab-carbon" onclick="setTab('carbon')">탄소배출량</button>
    <button id="tab-energy" onclick="setTab('energy')">에너지사용량</button>
  </div>
  <div class="filterbar">
    <div class="chips" id="filterChips"></div>
    <button class="ghost-btn" onclick="downloadCSV()">⬇ 데이터 다운로드 (CSV)</button>
  </div>
  <div class="chips" id="regionChips" style="margin-bottom:12px"></div>
  <div class="card rankwrap" id="rankList"></div>
  <div class="muted" id="perAreaNote" style="margin-top:8px;display:none">※ 면적당 지표는 캠퍼스 특성(호수·부속시설·병원 등 연면적 구성)에 따라 왜곡될 수 있으므로 참고용으로 활용해 주세요.</div>
  <div class="rank-note">
    <span class="muted">배출량·사용량이 낮은 순으로 정렬됩니다. 막대를 클릭하면 학교 상세 페이지로 이동합니다.</span>
    <span class="muted" id="rankUnit"></span>
  </div>
</main>

<!-- ================= 상세 페이지 ================= -->
<main class="page" id="page-detail">
  <div class="crumb">
    <button onclick="go('home')">홈</button> ›
    <button onclick="go('compare')">학교 비교 데이터</button> ›
    <span id="crumbSchool"></span>
  </div>
  <div class="detail-head">
    <div>
      <h2 id="dName"></h2>
      <div class="badge-rank" id="dBadge"></div>
    </div>
    <button class="iconbtn" title="공유하기" onclick="shareSchool()">🔗</button>
  </div>

  <div class="kpigrid" id="dKpis"></div>

  <div class="tabs" style="margin-top:6px">
    <button id="dtab-carbon" onclick="setDetailTab('carbon')">탄소배출량</button>
    <button id="dtab-energy" onclick="setDetailTab('energy')">에너지사용량</button>
    <button id="dtab-info" onclick="setDetailTab('info')">기타정보</button>
  </div>

  <div id="dChartArea" class="card linechart-card"></div>
  <div id="dInfoArea" class="infogrid" style="display:none"></div>

  <h3 class="section-title" style="margin-top:26px">비슷한 규모의 학교</h3>
  <div class="simgrid" id="dSimilar"></div>

  <div class="detail-cta">
    <button class="pill-btn" onclick="compareWithOthers()">다른 학교와 비교하기 →</button>
  </div>
</main>


<!-- ================= 전국 지도 ================= -->
<main class="page" id="page-map">
  <div class="crumb"><button onclick="go('home')">홈</button> › 전국 지도에서 찾기</div>
  <h3 class="section-title">🗺 전국 지도에서 대학 선택</h3>
  <div class="mapgrid">
    <div class="card mapcard">
      <div id="koreaMap"></div>
      <div class="muted" style="padding:0 16px 14px">점을 클릭하면 오른쪽에 학교 정보가 표시됩니다. <b style="color:var(--primary)">수도권 박스를 클릭하면 확대</b>됩니다.</div>
    </div>
    <div class="mapside">
      <div class="card mappanel" id="mapPanel">
        <div class="muted" style="padding:18px;text-align:center">지도에서 대학을 선택해 주세요 ⚡</div>
      </div>
    </div>
  </div>
</main>

<button class="sticky-cta" id="stickyCta" onclick="ctaClick()">🏫 우리 학교 비교하기</button>
<div class="toast" id="toast"></div>

<footer class="foot">
  ※ 본 화면의 수치는 플랫폼 구조 검증을 위한 <b>샘플 데이터</b>입니다. 실제 서비스 시 온실가스종합정보센터(배출권거래제·목표관리제 명세서), 대학알리미(재학생·전임교원·직원 수, 연면적) 데이터로 교체됩니다. 1인당 지표의 분모(총구성원수)는 재학생+전임교원+직원 합계 기준입니다. · 대학탄소중립협의체 2기
</footer>

<script>
/* ============================================================
   [데이터 영역] — 실제 데이터로 교체할 때는 이 부분만 수정하면 됩니다.
   각 학교: 이름, 제도유형, 총구성원수(명), 연면적(㎡),
   기준배출량(tCO2e), 연도별 탄소배출량(tCO2e), 연도별 에너지사용량(TJ),
   탄소배출권 구매액(백만원)
============================================================ */
const YEARS=[2021,2022,2023,2024,2025,2026];
// 연도별 수치 생성기(샘플): 시작값에서 연평균 감축률만큼 감소 + 소폭 변동
const wig=[0,0.004,-0.003,0.002,-0.002,0.001];
const gen=(v0,r)=>YEARS.map((_,i)=>Math.round(v0*Math.pow(1-r,i)*(1+wig[i])));
/* 필드: n=기관명, d=축약명, r=권역, s=제도(ETS=배출권거래제/TMS=목표관리제),
   p=총구성원수(재학생+전임교원+직원, 명), a=연면적(㎡), b=기준배출량(tCO2e),
   c=연도별 탄소배출량, e=연도별 에너지사용량(TJ), k=배출권 구매액(백만원) */
const SCHOOLS=[
 {n:"강원대학교", d:"강원대",r:"강원권",s:"TMS",p:24300,a:1050000,b:39000, c:gen(40300,0.022), e:gen(795,0.021), k:72},
 {n:"경북대학교", d:"경북대",r:"영남권",s:"TMS",p:27800,a:1180000,b:61000, c:gen(63100,0.021), e:gen(1247,0.020), k:120},
 {n:"경상국립대학교", d:"경상국립대",r:"영남권",s:"TMS",p:21500,a:980000,b:36000, c:gen(37200,0.020), e:gen(735,0.019), k:60},
 {n:"서울대학교", d:"서울대",r:"수도권",s:"ETS",p:34500,a:1620000,b:118000,c:gen(121000,0.023),e:gen(2380,0.022),k:420},
 {n:"부산대학교", d:"부산대",r:"영남권",s:"TMS",p:28900,a:1230000,b:66000, c:gen(68200,0.021), e:gen(1347,0.020), k:150},
 {n:"전남대학교", d:"전남대",r:"호남권",s:"TMS",p:24600,a:1090000,b:52000, c:gen(53800,0.020), e:gen(1063,0.019), k:95},
 {n:"전북대학교", d:"전북대",r:"호남권",s:"TMS",p:23200,a:1020000,b:47000, c:gen(48600,0.019), e:gen(960,0.019), k:85},
 {n:"충남대학교", d:"충남대",r:"충청권",s:"TMS",p:22400,a:990000,b:45500, c:gen(47100,0.020), e:gen(930,0.019), k:80},
 {n:"충북대학교", d:"충북대",r:"충청권",s:"TMS",p:18700,a:830000,b:37000, c:gen(38300,0.019), e:gen(757,0.018), k:65},
 {n:"학교법인 가톨릭학원", d:"가톨릭학원",r:"수도권",s:"ETS",p:19800,a:960000,b:95000, c:gen(98400,0.022), e:gen(1944,0.021), k:340},
 {n:"학교법인 건국대학교", d:"건국대학교",r:"수도권",s:"TMS",p:23900,a:880000,b:52000, c:gen(53900,0.020), e:gen(1065,0.019), k:98},
 {n:"학교법인 경희학원", d:"경희학원",r:"수도권",s:"TMS",p:26700,a:920000,b:62000, c:gen(64100,0.021), e:gen(1266,0.020), k:118},
 {n:"학교법인 계명대학교", d:"계명대학교",r:"영남권",s:"TMS",p:18200,a:790000,b:48000, c:gen(49700,0.019), e:gen(982,0.018), k:88},
 {n:"학교법인 고려중앙학원", d:"고려중앙학원",r:"수도권",s:"ETS",p:30100,a:1240000,b:120000,c:gen(123800,0.022),e:gen(2446,0.021),k:405},
 {n:"학교법인 성균관대학", d:"성균관대학",r:"수도권",s:"TMS",p:26200,a:1010000,b:74000, c:gen(75800,0.021), e:gen(1497,0.020), k:135},
 {n:"학교법인 연세대학교", d:"연세대학교",r:"수도권",s:"ETS",p:31400,a:1350000,b:150000,c:gen(154600,0.023),e:gen(3054,0.022),k:520},
 {n:"학교법인 영남학원", d:"영남학원",r:"영남권",s:"TMS",p:20400,a:900000,b:46000, c:gen(47600,0.019), e:gen(940,0.018), k:82},
 {n:"학교법인 이화학당", d:"이화학당",r:"수도권",s:"TMS",p:18600,a:700000,b:45000, c:gen(46300,0.020), e:gen(915,0.019), k:78},
 {n:"학교법인 중앙대학교", d:"중앙대학교",r:"수도권",s:"TMS",p:22800,a:850000,b:60000, c:gen(62000,0.021), e:gen(1225,0.020), k:112},
 {n:"학교법인 포항공과대학교", d:"포항공과대학교",r:"영남권",s:"ETS",p:5400,a:450000,b:41000, c:gen(42600,0.020), e:gen(842,0.019), k:130},
 {n:"학교법인 한양학원", d:"한양학원",r:"수도권",s:"TMS",p:27300,a:950000,b:71000, c:gen(73400,0.021), e:gen(1450,0.020), k:128}
];
/* ============================================================ */

const LAST=YEARS.length-1;
let mySchool=null;         // 선택된 '우리 학교' 이름
let curTab='carbon';       // 비교 페이지 탭
let curFilter='total';
let curRegion='all';        // 권역 필터     // total | percap | perarea
let curSchool=null;        // 상세 페이지 학교
let dTab='carbon';         // 상세 페이지 탭

const fmt=n=>n.toLocaleString('ko-KR');
const fmt1=n=>n.toLocaleString('ko-KR',{maximumFractionDigits:1});
const fmt2=n=>n.toLocaleString('ko-KR',{maximumFractionDigits:2});

function metricVal(s,tab,filter,yi=LAST){
  const base = tab==='carbon' ? s.c[yi] : s.e[yi];
  if(filter==='percap') return base/s.p*1000;   // 1인당(탄소:kgCO2e/명 → *1000, 에너지:GJ/명 → *1000)
  if(filter==='perarea')return base/s.a*1000;   // 면적당
  return base;
}
function unitOf(tab,filter){
  if(tab==='carbon'){
    if(filter==='percap') return 'kgCO₂e/명';
    if(filter==='perarea')return 'kgCO₂e/㎡';
    return 'tCO₂e';
  }else{
    if(filter==='percap') return 'GJ/명';
    if(filter==='perarea')return 'GJ/㎡';
    return 'TJ';
  }
}
function chg(arr){const p=arr[LAST-1],c=arr[LAST];return (c-p)/p*100;}
function deltaHTML(v,inline){
  const cls=v<=0?'down':'up';
  const arrow=v<=0?'▼':'▲';
  return `<span class="delta ${cls}" ${inline?'':''}>${arrow} ${Math.abs(v).toFixed(1)}%</span>`;
}

/* ---------- 페이지 전환 ---------- */
function go(page,tab){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById('page-'+page).classList.add('active');
  if(page==='compare'){ if(tab) curTab=tab; renderCompare(); }
  if(page==='home') renderHome();
  if(page==='map') renderMap();
  window.scrollTo({top:0,behavior:'smooth'});
}

/* ---------- 홈 ---------- */
function natTotals(key){
  return YEARS.map((_,yi)=>SCHOOLS.reduce((a,s)=>a+s[key][yi],0));
}
function renderHome(){
  const c=natTotals('c'), e=natTotals('e');
  const cChg=chg(c), eChg=chg(e);
  document.getElementById('heroDelta').outerHTML=deltaHTML(cChg).replace('class="delta','id="heroDelta" class="delta');
  document.getElementById('natCarbonVal').innerHTML=fmt(Math.round(c[LAST]/1000))+'<small>천 tCO₂e</small>';
  document.getElementById('natEnergyVal').innerHTML=fmt(Math.round(e[LAST]))+'<small>TJ</small>';
  document.getElementById('natCarbonChg').innerHTML='전년 대비 '+deltaHTML(cChg);
  document.getElementById('natEnergyChg').innerHTML='전년 대비 '+deltaHTML(eChg);
  drawMini('natCarbonChart',c); drawMini('natEnergyChart',e);
}
function drawMini(id,arr){
  const el=document.getElementById(id); el.innerHTML='';
  const max=Math.max(...arr);
  arr.forEach((v,i)=>{
    const b=document.createElement('div');
    b.className='bar'+(i===LAST?' last':'');
    b.style.height=(v/max*100)+'%';
    b.innerHTML=`<span>${YEARS[i]}</span>`;
    b.title=fmt(Math.round(v));
    el.appendChild(b);
  });
}

/* ---------- 검색 ---------- */
const sInput=document.getElementById('searchInput');
const sDrop=document.getElementById('searchDrop');
function renderSearchList(){
  const q=sInput.value.trim().toLowerCase();
  const ranked=[...SCHOOLS].sort((a,b)=>a.c[LAST]-b.c[LAST]);
  const rankMap={}; ranked.forEach((s,i)=>rankMap[s.n]=i+1);
  let list=[...SCHOOLS].sort((a,b)=>a.n.localeCompare(b.n,'ko'));   // 가나다순
  if(q) list=list.filter(s=>s.n.toLowerCase().includes(q));
  sDrop.innerHTML = list.length
    ? list.map(s=>`<button onclick="pickSchool('${s.n}')"><span>${s.n}</span><span class="rk">탄소배출 전국 ${rankMap[s.n]}위</span></button>`).join('')
    : `<button disabled style="color:var(--ink-soft)">검색 결과가 없습니다</button>`;
  sDrop.classList.add('open');
}
sInput.addEventListener('input',renderSearchList);
sInput.addEventListener('focus',renderSearchList);
document.addEventListener('click',e=>{
  if(!e.target.closest('.searchwrap')) sDrop.classList.remove('open');
});
function pickSchool(name){
  sDrop.classList.remove('open'); sInput.value='';
  if(!mySchool){ setMySchool(name); }
  openDetail(name);
}
function setMySchool(name){
  mySchool=name;
  const chip=document.getElementById('myChip');
  document.getElementById('myChipName').textContent='우리 학교: '+name;
  chip.classList.add('on');
  toast(`'${name}'을(를) 우리 학교로 설정했어요`);
}
function clearMySchool(e){
  e.stopPropagation(); mySchool=null;
  document.getElementById('myChip').classList.remove('on');
  if(document.getElementById('page-compare').classList.contains('active')) renderCompare();
}
function ctaClick(){
  if(mySchool){ go('compare'); }
  else{ sInput.focus(); toast('먼저 검색창에서 우리 학교를 선택해 주세요'); }
}

/* ---------- 비교 페이지 ---------- */
function setTab(t){ curTab=t; if(t==='energy'&&curFilter==='total') curFilter='percap'; if(t==='carbon'&&!['total','percap','perarea'].includes(curFilter)) curFilter='total'; renderCompare(); }
function setFilter(f){ curFilter=f; renderCompare(); }
function setRegion(r){ curRegion=r; renderCompare(); }
function renderCompare(){
  document.getElementById('tab-carbon').classList.toggle('on',curTab==='carbon');
  document.getElementById('tab-energy').classList.toggle('on',curTab==='energy');
  // 필터: 탄소=총/1인당/면적당, 에너지=1인당/면적당 (기획안 3-2)
  const defs = curTab==='carbon'
    ? [['total','총배출량'],['percap','1인당'],['perarea','면적당']]
    : [['percap','1인당'],['perarea','면적당']];
  if(!defs.some(d=>d[0]===curFilter)) curFilter=defs[0][0];
  document.getElementById('filterChips').innerHTML=defs.map(([k,l])=>
    `<button class="chip ${curFilter===k?'on':''}" onclick="setFilter('${k}')">${l}</button>`).join('');
  const unit=unitOf(curTab,curFilter);
  document.getElementById('rankUnit').textContent='단위: '+unit;
  // 권역별 보기 (수도권/비수도권 이분 대신 중립적 권역 구분)
  const regions=['all','수도권','강원권','충청권','호남권','영남권'];
  document.getElementById('regionChips').innerHTML=regions.map(r=>
    `<button class="chip ${curRegion===r?'on':''}" onclick="setRegion('${r}')">${r==='all'?'전체 권역':r}</button>`).join('');
  document.getElementById('perAreaNote').style.display = curFilter==='perarea' ? 'block' : 'none';

  const pool=SCHOOLS.filter(s=>curRegion==='all'||s.r===curRegion);
  const rows=pool.map(s=>({s,v:metricVal(s,curTab,curFilter)})).sort((a,b)=>a.v-b.v);
  const max=Math.max(...rows.map(r=>r.v));
  const list=document.getElementById('rankList');
  list.innerHTML=rows.map((r,i)=>{
    const mine=r.s.n===mySchool?' mine':'';
    const valTxt = curFilter==='total'
      ? fmt(Math.round(r.v)) : (r.v>=100?fmt(Math.round(r.v)):fmt2(r.v));
    return `<div class="rankrow${mine}" onclick="openDetail('${r.s.n}')">
      <div class="num">${i+1}</div>
      <div class="name" title="${r.s.n}">${r.s.d}</div>
      <div class="barcell"><div class="barfill" style="width:0%" data-w="${(r.v/max*100).toFixed(1)}"></div></div>
      <div class="val">${valTxt}</div>
    </div>`;
  }).join('');
  requestAnimationFrame(()=>requestAnimationFrame(()=>{
    list.querySelectorAll('.barfill').forEach(b=>b.style.width=b.dataset.w+'%');
  }));
  // 우리 학교로 스크롤 힌트
  const mine=list.querySelector('.rankrow.mine');
  if(mine) setTimeout(()=>mine.scrollIntoView({block:'center',behavior:'smooth'}),350);
}
function downloadCSV(){
  const unit=unitOf(curTab,curFilter);
  let csv='\uFEFF순위,기관명,값('+unit+'),권역,제도유형,총구성원수(명),연면적(㎡)\n';
  const rows=SCHOOLS.filter(s=>curRegion==='all'||s.r===curRegion).map(s=>({s,v:metricVal(s,curTab,curFilter)})).sort((a,b)=>a.v-b.v);
  rows.forEach((r,i)=>{csv+=`${i+1},${r.s.n},${r.v.toFixed(2)},${r.s.r},${instName(r.s.s)},${r.s.p},${r.s.a}\n`;});
  const blob=new Blob([csv],{type:'text/csv;charset=utf-8'});
  const a=document.createElement('a');
  a.href=URL.createObjectURL(blob);
  a.download=`KUCE_${curTab==='carbon'?'탄소배출량':'에너지사용량'}_${curFilter}.csv`;
  a.click(); URL.revokeObjectURL(a.href);
  toast('CSV 파일을 다운로드했어요');
}
function instName(s){return s==='ETS'?'배출권거래제':s==='TMS'?'목표관리제':'미포함';}

/* ---------- 상세 페이지 ---------- */
function openDetail(name){
  curSchool=SCHOOLS.find(s=>s.n===name);
  if(!curSchool) return;
  dTab='carbon';
  renderDetail();
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById('page-detail').classList.add('active');
  window.scrollTo({top:0,behavior:'smooth'});
}
function rankOf(s,tab='carbon'){
  const sorted=[...SCHOOLS].sort((a,b)=>metricVal(a,tab,'total')-metricVal(b,tab,'total'));
  return sorted.findIndex(x=>x.n===s.n)+1;
}
function renderDetail(){
  const s=curSchool;
  document.getElementById('crumbSchool').textContent=s.n;
  document.getElementById('dName').textContent=s.n;
  const rk=rankOf(s,'carbon');
  document.getElementById('dBadge').innerHTML=`전국 ${rk}위 <small>/ ${SCHOOLS.length}개교 · 탄소배출량 낮은 순</small>`;

  const cChg=chg(s.c), eChg=chg(s.e);
  const dev = s.b>0 ? s.c[LAST]-s.b : null;               // 기준대비 증감량
  const devPct = s.b>0 ? (s.c[LAST]-s.b)/s.b*100 : null;  // 기준대비 증감률
  document.getElementById('dKpis').innerHTML=`
    <div class="card kpi"><div class="k-label">탄소배출량 (2026)</div>
      <div class="k-val">${fmt(s.c[LAST])}<small>tCO₂e</small></div>
      <div class="k-chg">${deltaHTML(cChg)} <span class="muted">전년 대비</span></div></div>
    <div class="card kpi"><div class="k-label">에너지사용량 (2026)</div>
      <div class="k-val">${fmt(s.e[LAST])}<small>TJ</small></div>
      <div class="k-chg">${deltaHTML(eChg)} <span class="muted">전년 대비</span></div></div>
    <div class="card kpi"><div class="k-label">1인당 탄소배출량</div>
      <div class="k-val">${fmt1(s.c[LAST]/s.p*1000)}<small>kgCO₂e/명</small></div>
      <div class="k-chg"><span class="muted">재학생+전임교원+직원 ${fmt(s.p)}명 기준</span></div></div>
    <div class="card kpi"><div class="k-label">기준배출량 대비</div>
      <div class="k-val">${dev===null?'—':(dev<=0?'−':'+')+fmt(Math.abs(Math.round(dev)))}<small>${dev===null?'기준 없음':'tCO₂e'}</small></div>
      <div class="k-chg">${devPct===null?'<span class="muted">제도 미포함</span>':deltaHTML(devPct)+' <span class="muted">'+(dev<=0?'감축 여유분 확보':'초과 배출')+'</span>'}</div></div>`;

  setDetailTab(dTab);
  renderSimilar();
}
function setDetailTab(t){
  dTab=t;
  ['carbon','energy','info'].forEach(k=>
    document.getElementById('dtab-'+k).classList.toggle('on',k===t));
  const chartArea=document.getElementById('dChartArea');
  const infoArea=document.getElementById('dInfoArea');
  if(t==='info'){
    chartArea.style.display='none'; infoArea.style.display='grid';
    renderInfo();
  }else{
    chartArea.style.display='block'; infoArea.style.display='none';
    drawLine(chartArea, t==='carbon'?curSchool.c:curSchool.e,
      t==='carbon'?'탄소배출량 (tCO₂e)':'에너지사용량 (TJ)');
  }
}
function renderInfo(){
  const s=curSchool;
  const items=[
    ['제도유형',instName(s.s)],
    ['권역',s.r],
    ['총구성원수 (재학생+전임교원+직원, 대학알리미 기준)',fmt(s.p)+'명'],
    ['캠퍼스 연면적',fmt(s.a)+'㎡'],
    ['기준배출량',s.b>0?fmt(s.b)+' tCO₂e':'해당 없음'],
    ['기준대비 증감량',s.b>0?((s.c[LAST]-s.b<=0?'−':'+')+fmt(Math.abs(s.c[LAST]-s.b))+' tCO₂e'):'—'],
    ['기준대비 증감률',s.b>0?((s.c[LAST]-s.b)/s.b*100).toFixed(1)+'%':'—'],
    ['감축 여유분',s.b>0&&s.c[LAST]<=s.b?fmt(s.b-s.c[LAST])+' tCO₂e':'—'],
    ['초과 배출량',s.b>0&&s.c[LAST]>s.b?fmt(s.c[LAST]-s.b)+' tCO₂e':'없음'],
    ['탄소배출권 구매액(연간)',s.k>0?fmt(s.k)+'백만 원':'—'],
    ['면적당 탄소배출량',fmt2(s.c[LAST]/s.a*1000)+' kgCO₂e/㎡'],
    ['면적당 에너지사용량',fmt2(s.e[LAST]/s.a*1000)+' GJ/㎡'],
    ['1인당 에너지사용량',fmt1(s.e[LAST]/s.p*1000)+' GJ/명'],
    ['1인당 감축 포인트 ('+YEARS[0]+'→'+YEARS[LAST]+')',(()=>{const p0=s.c[0]/s.p,p1=s.c[LAST]/s.p;const d=(p0-p1)/p0*100;return (d>=0?'−':'+')+Math.abs(d).toFixed(1)+'% 누적 감축';})()],
  ];
  document.getElementById('dInfoArea').innerHTML=items.map(([l,v])=>
    `<div class="card inforow"><span class="il">${l}</span><span class="iv">${v}</span></div>`).join('')
    +`<div class="muted" style="grid-column:1/-1">※ 면적당 지표는 캠퍼스 특성(호수·부속시설·병원 등)에 따라 왜곡될 수 있습니다. · 1인당 지표의 분모는 재학생+전임교원+직원 합계입니다.</div>`;
}
function drawLine(container,arr,label){
  const W=760,H=280,P={l:64,r:20,t:24,b:34};
  const min=Math.min(...arr)*0.985, max=Math.max(...arr)*1.015;
  const x=i=>P.l+(W-P.l-P.r)*i/(arr.length-1);
  const y=v=>P.t+(H-P.t-P.b)*(1-(v-min)/(max-min));
  let grid='',labels='';
  for(let g=0;g<=3;g++){
    const gv=min+(max-min)*g/3, gy=y(gv);
    grid+=`<line x1="${P.l}" y1="${gy}" x2="${W-P.r}" y2="${gy}" stroke="#24436B" stroke-width="1.5"/>`;
    labels+=`<text x="${P.l-8}" y="${gy+4}" text-anchor="end" font-size="11" fill="#9FB4CC">${fmt(Math.round(gv))}</text>`;
  }
  const pts=arr.map((v,i)=>`${x(i)},${y(v)}`).join(' ');
  const area=`${P.l},${H-P.b} ${pts} ${W-P.r},${H-P.b}`;
  let dots='',xls='';
  arr.forEach((v,i)=>{
    dots+=`<circle cx="${x(i)}" cy="${y(v)}" r="${i===LAST?6:4.5}" fill="${i===LAST?'#F5C84B':'#6FB0E8'}" stroke="#0E2A4E" stroke-width="2"><link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700;800;900&display=swap" rel="stylesheet">
<title>${YEARS[i]}년: ${fmt(v)}</title></circle>`;
    xls+=`<text x="${x(i)}" y="${H-P.b+20}" text-anchor="middle" font-size="11.5" fill="#9FB4CC">${YEARS[i]}</text>`;
  });
  const lastV=arr[LAST];
  container.innerHTML=`
    <div style="display:flex;justify-content:space-between;align-items:baseline;margin-bottom:8px">
      <b style="font-size:14.5px">연도별 ${label}</b>
      <span class="muted">2026년: <b style="color:var(--primary)">${fmt(lastV)}</b></span>
    </div>
    <svg viewBox="0 0 ${W} ${H}" role="img" aria-label="연도별 ${label} 추이">
      ${grid}${labels}
      <polygon points="${area}" fill="rgba(111,176,232,.15)"/>
      <polyline points="${pts}" fill="none" stroke="#6FB0E8" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
      ${dots}${xls}
    </svg>
    <div class="muted" style="margin-top:6px">점에 마우스를 올리면 연도별 수치를 확인할 수 있어요.</div>
    ${seasonHTML(arr[LAST],label)}`;
}

/* 계절별 분포(냉난방 반영 샘플 — 공식 월별 자료 확보 시 실데이터로 교체) */
function seasonHTML(annual,label){
  const seasons=[['봄',0.21],['여름',0.29],['가을',0.20],['겨울',0.30]];
  const max=Math.max(...seasons.map(s=>s[1]));
  const bars=seasons.map(([nm,sh])=>{
    const v=annual*sh;
    return `<div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:6px">
      <div style="font-size:12px;font-weight:800;color:#fff">${fmt(Math.round(v))}</div>
      <div style="width:70%;max-width:56px;height:${(sh/max*90).toFixed(0)}px;border-radius:8px 8px 4px 4px;
        background:${(nm==='여름'||nm==='겨울')?'linear-gradient(180deg,#FFD86B,#E0A428)':'linear-gradient(180deg,#6FB0E8,#3E7DC0)'}"></div>
      <div style="font-size:12px;color:var(--ink-soft)">${nm}</div>
    </div>`;
  }).join('');
  return `<div style="margin-top:22px;border-top:1px solid var(--line);padding-top:16px">
    <div style="display:flex;justify-content:space-between;align-items:baseline;margin-bottom:10px">
      <b style="font-size:14px">계절별 ${label.split(' ')[0]} 분포 <span class="muted">(${YEARS[LAST]}년)</span></b>
      <span class="muted">냉·난방 수요로 여름·겨울이 높게 나타납니다</span>
    </div>
    <div style="display:flex;align-items:flex-end;gap:8px">${bars}</div>
    <div class="muted" style="margin-top:8px">※ 계절 분포는 샘플 추정치입니다. 월별 공식 자료 확보 시 실측값으로 교체 예정.</div>
  </div>`;
}

function renderSimilar(){
  const s=curSchool;
  const sims=[...SCHOOLS].filter(x=>x.n!==s.n)
    .sort((a,b)=>Math.abs(a.p-s.p)-Math.abs(b.p-s.p)).slice(0,3);
  document.getElementById('dSimilar').innerHTML=sims.map(x=>{
    const r=rankOf(x,'carbon');
    return `<div class="card simcard" onclick="openDetail('${x.n}')">
      <div class="sn">${x.d} <span class="muted">· 전국 ${r}위</span></div>
      <div class="sv">구성원 ${fmt(x.p)}명 · ${fmt(x.c[LAST])} tCO₂e</div>
    </div>`;
  }).join('');
}
function shareSchool(){
  const s=curSchool, r=rankOf(s,'carbon');
  const txt=`[KUCE] ${s.n} — 대학 탄소배출량 전국 ${r}위 / ${SCHOOLS.length}개교 · 2026년 ${fmt(s.c[LAST])} tCO₂e (전년 대비 ${chg(s.c).toFixed(1)}%)`;
  if(navigator.clipboard){ navigator.clipboard.writeText(txt).then(()=>toast('공유 문구를 복사했어요! SNS에 붙여넣기 하세요 📋')); }
  else toast(txt);
}
function compareWithOthers(){
  if(curSchool && !mySchool) setMySchool(curSchool.n);
  else if(curSchool) mySchool=curSchool.n, setMySchool(curSchool.n);
  go('compare');
}
let toastTimer;
function toast(msg){
  const t=document.getElementById('toast');
  t.textContent=msg; t.classList.add('show');
  clearTimeout(toastTimer);
  toastTimer=setTimeout(()=>t.classList.remove('show'),2600);
}


/* ---------- 전국 지도 ---------- */
const COORDS={ // [위도, 경도]
 "강원대학교":[37.869,127.744],"경북대학교":[35.890,128.612],"경상국립대학교":[35.154,128.098],
 "서울대학교":[37.459,126.952],"부산대학교":[35.233,129.079],"전남대학교":[35.176,126.906],
 "전북대학교":[35.847,127.129],"충남대학교":[36.368,127.344],"충북대학교":[36.628,127.457],
 "학교법인 가톨릭학원":[37.487,126.801],"학교법인 건국대학교":[37.540,127.079],
 "학교법인 경희학원":[37.596,127.052],"학교법인 계명대학교":[35.855,128.489],
 "학교법인 고려중앙학원":[37.589,127.032],"학교법인 성균관대학":[37.588,126.993],
 "학교법인 연세대학교":[37.566,126.938],"학교법인 영남학원":[35.836,128.754],
 "학교법인 이화학당":[37.562,126.947],"학교법인 중앙대학교":[37.505,126.957],
 "학교법인 포항공과대학교":[36.013,129.325],"학교법인 한양학원":[37.557,127.045]
};
// 간이 해안선 (경도,위도) — 스타일화된 대한민국 윤곽
const COAST=[
 [126.68,37.80],[127.05,38.30],[127.80,38.32],[128.35,38.60],[128.60,38.58],
 [128.90,38.10],[129.10,37.60],[129.35,37.05],[129.42,36.55],[129.57,36.05],
 [129.45,35.55],[129.25,35.30],[129.00,35.05],[128.60,34.90],[128.10,34.85],
 [127.70,34.60],[127.30,34.45],[126.85,34.30],[126.50,34.30],[126.28,34.70],
 [126.40,35.10],[126.68,35.60],[126.52,36.00],[126.48,36.70],[126.15,36.75],
 [126.35,37.00],[126.62,37.20],[126.55,37.55],[126.68,37.80]
];
function projFactory(lngMin,lngMax,latMin,latMax,W,H,pad){
  return ([lat,lng])=>[
    pad+(lng-lngMin)/(lngMax-lngMin)*(W-2*pad),
    pad+(latMax-lat)/(latMax-latMin)*(H-2*pad)
  ];
}
let mapSelected=null;
let mapView='national';   // national | seoul
const SEOUL_B={latMin:37.05,latMax:37.75,lngMin:126.40,lngMax:127.30};
const inSeoulArea=n=>{const[la,lo]=COORDS[n];
  return la>SEOUL_B.latMin&&la<SEOUL_B.latMax&&lo>SEOUL_B.lngMin&&lo<SEOUL_B.lngMax;};

/* ---- 라벨 자동 배치: 우→좌→위→아래 순으로 빈 자리를 찾고, 없으면 아래로 밀어냄 ---- */
function estW(t,fs){return t.length*fs+6;}
function placeLabels(nodes,W,H,fs){
  const placed=[];
  const boxOf=(lx,ly,w,anchor)=>{
    const x0=anchor==='start'?lx:anchor==='end'?lx-w:lx-w/2;
    return {x0,x1:x0+w,y0:ly-fs+1,y1:ly+3};
  };
  const clash=b=>placed.some(p=>!(b.x1<p.x0||b.x0>p.x1||b.y1<p.y0||b.y0>p.y1))
    || b.x0<2||b.x1>W-2||b.y0<2||b.y1>H-2;
  const sorted=[...nodes].sort((a,b)=>a.y-b.y);
  const out=[];
  for(const nd of sorted){
    const w=estW(nd.text,fs);
    const cands=[
      {lx:nd.x+10,ly:nd.y+4,anchor:'start'},
      {lx:nd.x-10,ly:nd.y+4,anchor:'end'},
      {lx:nd.x,   ly:nd.y-12,anchor:'middle'},
      {lx:nd.x,   ly:nd.y+20,anchor:'middle'}
    ];
    let pick=null;
    for(const c of cands){ if(!clash(boxOf(c.lx,c.ly,w,c.anchor))){pick=c;break;} }
    if(!pick){
      pick={lx:nd.x+10,ly:nd.y+4,anchor:'start'};
      let tries=0;
      while(clash(boxOf(pick.lx,pick.ly,w,pick.anchor))&&tries<14){pick.ly+=fs+3;tries++;}
    }
    placed.push(boxOf(pick.lx,pick.ly,w,pick.anchor));
    out.push({...nd,...pick,far:Math.abs(pick.ly-nd.y)>16||Math.abs(pick.lx-nd.x)>60});
  }
  return out;
}
function labelSVG(L,color){
  let s='';
  if(L.far){ // 라벨이 멀리 밀렸으면 연결선 표시
    const tx=L.anchor==='start'?L.lx-3:L.anchor==='end'?L.lx+3:L.lx;
    s+=`<line x1="${L.x}" y1="${L.y}" x2="${tx}" y2="${L.ly-4}" stroke="${color}" stroke-width=".7" opacity=".5"/>`;
  }
  s+=`<text class="maplabel" x="${L.lx.toFixed(1)}" y="${L.ly.toFixed(1)}" text-anchor="${L.anchor}" font-size="${L.fs}" fill="${color}">${L.text}</text>`;
  return s;
}
function toggleMapView(v){ mapView=v; renderMap(); }

function renderMap(){
  const el=document.getElementById('koreaMap');
  el.innerHTML = mapView==='seoul' ? seoulSVG() : nationalSVG();
  renderMapPanel();
}

/* ---- 전국 뷰 ---- */
function nationalSVG(){
  const W=380,H=500,pad=24,fs=10.5;
  const P=projFactory(125.6,129.9,33.0,38.8,W,H,pad);
  const path=COAST.map((c,i)=>(i?'L':'M')+P([c[1],c[0]]).map(v=>v.toFixed(1)).join(',')).join(' ')+' Z';
  const jeju=P([33.38,126.53]);
  let dots='',nodes=[];
  for(const s of SCHOOLS){
    const[x,y]=P(COORDS[s.n]);
    const sel=mapSelected===s.n;
    const seoul=inSeoulArea(s.n);
    dots+=`<circle class="mapdot" cx="${x.toFixed(1)}" cy="${y.toFixed(1)}" r="${sel?8:(seoul?3.5:7)}"
      fill="${sel?'#F5C84B':(s.n===mySchool?'#F5C84B':'#6FB0E8')}" stroke="#0E2A4E" stroke-width="1.5"
      onclick="${seoul?"toggleMapView('seoul')":`selectOnMap('${s.n}')`}"><title>${s.n}</title></circle>`;
    if(!seoul) nodes.push({x,y,text:s.d,fs,sel});
  }
  const labels=placeLabels(nodes,W,H,fs).map(L=>labelSVG(L,L.sel?'#F5C84B':'#9FB4CC')).join('');
  const b1=P([SEOUL_B.latMax,SEOUL_B.lngMin]), b2=P([SEOUL_B.latMin,SEOUL_B.lngMax]);
  return `
  <svg viewBox="0 0 ${W} ${H}" role="img" aria-label="전국 대학 지도">
    <path d="${path}" fill="#16395F" stroke="#3E6493" stroke-width="1.5"/>
    <ellipse cx="${jeju[0]}" cy="${jeju[1]}" rx="20" ry="9" fill="#16395F" stroke="#3E6493" stroke-width="1.5"/>
    ${dots}${labels}
    <g class="mapdot" onclick="toggleMapView('seoul')" style="cursor:pointer">
      <rect x="${b1[0].toFixed(1)}" y="${b1[1].toFixed(1)}"
        width="${(b2[0]-b1[0]).toFixed(1)}" height="${(b2[1]-b1[1]).toFixed(1)}" rx="8"
        fill="rgba(245,200,75,.10)" stroke="#F5C84B" stroke-width="1.4" stroke-dasharray="5 3"/>
      <text x="${((b1[0]+b2[0])/2).toFixed(1)}" y="${(b1[1]-7).toFixed(1)}" text-anchor="middle"
        font-size="11.5" font-weight="800" fill="#F5C84B">수도권 🔍 클릭하여 확대</text>
    </g>
  </svg>`;
}

/* ---- 수도권 확대 뷰 ---- */
function seoulSVG(){
  const W=520,H=430,pad=46,fs=11.5;
  const P=projFactory(126.72,127.16,37.42,37.66,W,H,pad);
  let dots='',nodes=[];
  for(const s of SCHOOLS){
    if(!inSeoulArea(s.n)) continue;
    const[x,y]=P(COORDS[s.n]);
    const sel=mapSelected===s.n;
    dots+=`<circle class="mapdot" cx="${x.toFixed(1)}" cy="${y.toFixed(1)}" r="${sel?10:7.5}"
      fill="${sel?'#F5C84B':(s.n===mySchool?'#F5C84B':'#6FB0E8')}" stroke="#0E2A4E" stroke-width="1.5"
      onclick="selectOnMap('${s.n}')"><title>${s.n}</title></circle>`;
    nodes.push({x,y,text:s.d,fs,sel});
  }
  const labels=placeLabels(nodes,W,H,fs).map(L=>labelSVG(L,L.sel?'#F5C84B':'#C7D6E8')).join('');
  return `
  <div style="padding:6px 12px 4px">
    <button class="ghost-btn" onclick="toggleMapView('national')">← 전국 지도로 돌아가기</button>
  </div>
  <svg viewBox="0 0 ${W} ${H}" role="img" aria-label="수도권 대학 확대 지도">
    <rect x="6" y="6" width="${W-12}" height="${H-12}" rx="16" fill="#10315B" stroke="#3E6493" stroke-width="1.5"/>
    <text x="24" y="34" font-size="14" font-weight="900" fill="#F5C84B">수도권</text>
    ${dots}${labels}
  </svg>`;
}
function selectOnMap(name){ mapSelected=name; renderMap(); }
function renderMapPanel(){
  const p=document.getElementById('mapPanel');
  if(!mapSelected){
    p.innerHTML='<div class="muted" style="padding:18px;text-align:center">지도에서 대학을 선택해 주세요 ⚡</div>';
    return;
  }
  const s=SCHOOLS.find(x=>x.n===mapSelected);
  const r=rankOf(s,'carbon');
  p.innerHTML=`<div class="mp-in">
    <div class="mp-name">${s.n}</div>
    <div class="mp-rank">전국 ${r}위 / ${SCHOOLS.length}개교</div>
    <div class="mp-stat">
      탄소배출량 <b>${fmt(s.c[LAST])} tCO₂e</b> (${chg(s.c).toFixed(1)}%)<br>
      에너지사용량 <b>${fmt(s.e[LAST])} TJ</b><br>
      1인당 배출량 <b>${fmt1(s.c[LAST]/s.p*1000)} kgCO₂e/명</b>
    </div>
    <div style="display:flex;gap:8px;margin-top:14px;flex-wrap:wrap">
      <button class="pill-btn" style="padding:9px 18px;font-size:13.5px" onclick="openDetail('${s.n}')">상세 페이지 보기 →</button>
      <button class="ghost-btn" onclick="setMySchool('${s.n}');renderMap()">우리 학교로 설정</button>
    </div>
  </div>`;
}

renderHome();
</script>
</body>
</html>
