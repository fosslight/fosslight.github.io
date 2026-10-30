---
layout: post
title: 제6회 FOSSLight Community Day
description: >
  2026.10.28 제6회 FOSSLight Community Day가 개최되었습니다.
hide_description: true
hide_last_modified: true
---

2026년 10월 28일, 제6회 FOSSLight Community Day가 서울 서초구에서 열렸습니다. FOSSLight Scanner와 Hub의 최신 기능부터 변화하는 SBOM 규제와 트렌드, ETRI의 FOSSLight 활용 사례, Scanner·Hub 질의응답과 FOSSLight Enterprise 소개까지 이어진 하루를 돌아봅니다.

<style>
.flcd{--fl-bg:#0b0912;--fl-panel:#141020;--fl-panel-2:#1c1629;--fl-line:rgba(255,255,255,.08);--fl-line-2:rgba(255,255,255,.15);--fl-sub:#c6bed8;--fl-mute:#9a92b1;--fl-grad:linear-gradient(100deg,#a78bfa 0%,#f472b6 50%,#fb923c 100%);--fl-mono:ui-monospace,SFMono-Regular,Menlo,Consolas,"Liberation Mono",monospace;position:relative;isolation:isolate;margin:2rem 0 3rem;padding:clamp(12px,2.4vw,24px);border-radius:28px;background:var(--fl-bg);color:#f5f2fc;font-family:"Pretendard","Noto Sans KR","Apple SD Gothic Neo","Malgun Gothic",system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;font-size:16px;line-height:1.7;word-break:keep-all;overflow-wrap:break-word;overflow:hidden;box-shadow:0 30px 80px -24px rgba(24,10,48,.6)}
.flcd::before{content:"";position:absolute;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(40rem 28rem at -10% -4%,rgba(139,92,246,.30),transparent 60%),radial-gradient(34rem 26rem at 110% 34%,rgba(236,72,153,.16),transparent 60%),radial-gradient(42rem 30rem at 40% 104%,rgba(249,115,22,.16),transparent 60%)}
.flcd::after{content:"";position:absolute;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.04) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.04) 1px,transparent 1px);background-size:40px 40px;-webkit-mask-image:linear-gradient(180deg,transparent 8%,#000 26%,transparent 62%);mask-image:linear-gradient(180deg,transparent 8%,#000 26%,transparent 62%)}
.flcd a{color:inherit;text-decoration:none;border-bottom:0}
.flcd-hero{position:relative;isolation:isolate;display:flex;align-items:flex-end;min-height:clamp(380px,46vw,480px);border-radius:22px;overflow:hidden;background:#140f22;border:1px solid var(--fl-line-2)}
.flcd .flcd-hero>p{position:absolute;inset:0;z-index:-2;margin:0}
.flcd .flcd-hero>p>img{display:block;width:100%;height:100%;max-width:none;object-fit:cover;object-position:50% 40%}
.flcd-hero::after{content:"";position:absolute;inset:0;z-index:-1;background:linear-gradient(180deg,rgba(11,9,18,.2) 0%,rgba(11,9,18,.68) 38%,rgba(11,9,18,.96) 100%),linear-gradient(90deg,rgba(46,16,101,.72) 0%,rgba(46,16,101,0) 70%)}
.flcd-hero__body{width:100%;padding:clamp(20px,4vw,40px)}
.flcd-kicker{display:flex;flex-wrap:wrap;align-items:center;gap:10px 14px;margin-bottom:16px;font-family:var(--fl-mono);font-size:12px;font-weight:600;letter-spacing:.16em;text-transform:uppercase;color:#ece6f8}
.flcd-live{display:inline-flex;align-items:center;gap:8px;padding:4px 11px;border-radius:999px;background:rgba(251,146,60,.16);border:1px solid rgba(251,146,60,.5);color:#ffd3ae;font-weight:800}
.flcd-live::before{content:"";width:7px;height:7px;border-radius:50%;background:#fb923c;box-shadow:0 0 0 4px rgba(251,146,60,.22)}
.flcd-hero__title{font-size:clamp(36px,6.2vw,66px);font-weight:900;line-height:1.04;letter-spacing:-.035em;color:#fff;text-shadow:0 6px 30px rgba(0,0,0,.35)}
.flcd-grad{background:var(--fl-grad);-webkit-background-clip:text;background-clip:text;color:transparent;-webkit-text-fill-color:transparent;text-shadow:none}
.flcd .flcd-hero__dek{max-width:34em;margin:18px 0 0;font-size:clamp(15px,1.7vw,18px);line-height:1.65;color:#e2dbf0}
.flcd-facts{display:flex;flex-wrap:wrap;gap:10px;margin-top:24px}
.flcd-fact{flex:1 1 120px;padding:10px 14px;border-radius:14px;background:rgba(14,10,24,.62);border:1px solid var(--fl-line-2);-webkit-backdrop-filter:blur(8px);backdrop-filter:blur(8px)}
.flcd-fact span{display:block;font-family:var(--fl-mono);font-size:10.5px;letter-spacing:.18em;text-transform:uppercase;color:#a99fc2}
.flcd-fact b{display:block;margin-top:2px;font-size:15px;font-weight:700;color:#fff}
.flcd-sec{margin-top:clamp(40px,6vw,64px);padding:0 clamp(4px,1.2vw,12px)}
.flcd-eyebrow{display:flex;align-items:center;gap:10px;margin-bottom:10px;font-family:var(--fl-mono);font-size:12px;font-weight:700;letter-spacing:.2em;text-transform:uppercase;color:#fdba74}
.flcd-eyebrow::before{content:"";width:22px;height:2px;border-radius:2px;background:var(--fl-grad)}
.flcd .flcd-h2{margin:0;font-family:inherit;font-size:clamp(24px,3.2vw,32px);font-weight:800;line-height:1.25;letter-spacing:-.02em;color:#fff}
.flcd .flcd-lede{margin:10px 0 0;font-size:15px;line-height:1.7;color:var(--fl-sub)}
.flcd-takeaways{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:14px;margin-top:22px}
.flcd-take{position:relative;padding:20px 20px 18px;border-radius:18px;background:linear-gradient(180deg,rgba(255,255,255,.055),rgba(255,255,255,.015));border:1px solid var(--fl-line)}
.flcd-take::before{content:"";position:absolute;left:20px;right:20px;top:-1px;height:2px;border-radius:2px;background:var(--fl-grad)}
.flcd-take__no{display:inline-block;font-family:var(--fl-mono);font-size:13px;font-weight:800;letter-spacing:.1em;background:var(--fl-grad);-webkit-background-clip:text;background-clip:text;color:transparent;-webkit-text-fill-color:transparent}
.flcd .flcd-take__title{margin:8px 0 6px;font-family:inherit;font-size:18px;font-weight:800;line-height:1.35;color:#fff}
.flcd .flcd-take__text{margin:0;font-size:14px;line-height:1.7;color:var(--fl-sub)}
.flcd-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:18px;margin-top:22px}
.flcd-card{display:flex;flex-direction:column;border-radius:20px;overflow:hidden;background:linear-gradient(180deg,var(--fl-panel-2),var(--fl-panel));border:1px solid var(--fl-line);transition:transform .2s ease,border-color .2s ease,box-shadow .2s ease}
.flcd-card:hover{transform:translateY(-3px);border-color:rgba(167,139,250,.5);box-shadow:0 18px 40px -12px rgba(124,58,237,.45)}
.flcd .flcd-card>p:first-child{margin:0;aspect-ratio:16/10;overflow:hidden;background:#120d1e}
.flcd .flcd-card>p:first-child>img{display:block;width:100%;height:100%;max-width:none;object-fit:cover;transition:transform .5s ease}
.flcd .flcd-card:hover>p:first-child>img{transform:scale(1.04)}
.flcd-card__body{flex:1;padding:18px 20px 4px}
.flcd-tag{display:inline-block;padding:3px 9px;border-radius:999px;font-family:var(--fl-mono);font-size:10.5px;font-weight:700;letter-spacing:.12em}
.flcd-tag--update{background:rgba(255,154,46,.14);color:#ffb766;border:1px solid rgba(255,154,46,.38)}
.flcd-tag--talk{background:rgba(224,160,255,.12);color:#e9c2ff;border:1px solid rgba(224,160,255,.34)}
.flcd-tag--ama{background:rgba(255,224,138,.12);color:#ffe7a3;border:1px solid rgba(255,224,138,.34)}
.flcd .flcd-card__title{margin:12px 0;font-family:inherit;font-size:18px;font-weight:800;line-height:1.4;letter-spacing:-.01em;color:#fff}
.flcd-speaker{display:flex;align-items:center;gap:10px}
.flcd-avatar{flex:0 0 34px;width:34px;height:34px;border-radius:50%;display:flex;align-items:center;justify-content:center;background:var(--fl-grad);color:#160f22;font-size:14px;font-weight:800}
.flcd-speaker b{display:block;font-size:14px;line-height:1.3;color:#fff}
.flcd-speaker small{display:block;font-size:12px;line-height:1.35;color:var(--fl-mute)}
.flcd .flcd-card__desc{margin:14px 0 0;font-size:14px;line-height:1.7;color:var(--fl-sub)}
.flcd .flcd-card>p:last-child{margin:0;padding:14px 20px 20px}
.flcd .flcd-card>p:last-child>a{display:inline-flex;align-items:center;gap:8px;padding:9px 14px;border:1px solid var(--fl-line-2);border-radius:12px;background:rgba(255,255,255,.05);color:#fff;font-size:13px;font-weight:700;text-decoration:none;transition:background .2s ease,color .2s ease}
.flcd .flcd-card>p:last-child>a:hover{background:#fff;color:#160f22;border-color:#fff}
.flcd-term{display:flex;flex-direction:column;aspect-ratio:16/10;overflow:hidden;background:radial-gradient(120% 90% at 0% 0%,rgba(139,92,246,.35),transparent 60%),#0e0b17;border-bottom:1px solid var(--fl-line)}
.flcd-term__bar{display:flex;align-items:center;gap:6px;padding:10px 14px;border-bottom:1px solid var(--fl-line);font-family:var(--fl-mono);font-size:11px;color:var(--fl-mute)}
.flcd-term__bar i{width:9px;height:9px;border-radius:50%;background:#ff5f57}
.flcd-term__bar i:nth-child(2){background:#febc2e}
.flcd-term__bar i:nth-child(3){background:#28c840}
.flcd-term__bar span{margin-left:8px}
.flcd-term__body{flex:1;display:flex;flex-direction:column;justify-content:center;gap:7px;padding:12px 18px;font-family:var(--fl-mono);font-size:12px;line-height:1.5;color:#ddd6ee}
.flcd-term__body em{margin-right:8px;font-style:normal;font-weight:800;color:#ffe08a}
.flcd-thanks{margin-bottom:clamp(8px,1.5vw,12px);padding:clamp(26px,4.5vw,44px) clamp(18px,4vw,40px);border-radius:22px;text-align:center;background:radial-gradient(60% 120% at 50% 0%,rgba(167,139,250,.28),transparent 70%),linear-gradient(180deg,var(--fl-panel-2),var(--fl-panel));border:1px solid var(--fl-line-2)}
.flcd-thanks .flcd-eyebrow{justify-content:center}
.flcd .flcd-thanks>p{max-width:34em;margin:14px auto 0;font-size:16px;line-height:1.75;color:var(--fl-sub)}
.flcd-partners{display:flex;flex-wrap:wrap;justify-content:center;align-items:center;gap:10px;margin-top:24px}
.flcd-partners span{width:100%;font-family:var(--fl-mono);font-size:11px;letter-spacing:.18em;text-transform:uppercase;color:var(--fl-mute)}
.flcd-partners b{padding:8px 14px;border-radius:12px;background:rgba(255,255,255,.06);border:1px solid var(--fl-line-2);font-size:14px;font-weight:700;color:#fff}
.flcd-ctas{display:flex;flex-wrap:wrap;justify-content:center;gap:10px;margin-top:24px}
.flcd .flcd-btn{display:inline-flex;align-items:center;gap:8px;padding:11px 18px;border:1px solid var(--fl-line-2);border-radius:12px;background:rgba(255,255,255,.05);color:#fff;font-size:14px;font-weight:700;text-decoration:none;transition:filter .2s ease,background .2s ease}
.flcd .flcd-btn:hover{background:rgba(255,255,255,.12)}
.flcd .flcd-btn--primary{background:var(--fl-grad);border-color:transparent;color:#160f22}
.flcd .flcd-btn--primary:hover{background:var(--fl-grad);filter:brightness(1.08)}
@media (max-width:720px){.flcd-takeaways,.flcd-grid{grid-template-columns:1fr}.flcd-hero{min-height:440px}.flcd-fact{flex-basis:100%;display:flex;align-items:baseline;justify-content:space-between;gap:12px;padding:9px 14px}.flcd-fact b{margin-top:0;text-align:right}}
@media (prefers-reduced-motion:reduce){.flcd *{transition:none!important}}
</style>

<div class="flcd" markdown="1">
<div class="flcd-hero" markdown="1">

![누구나 따라할 수 있는 FOSSLight Hub 시연 현장](../../assets/img/news/2510/20261028_110016.jpg)

<div class="flcd-hero__body">
<div class="flcd-kicker"><span class="flcd-live">Recap</span><span>Oct 28, 2026 · Seoul</span></div>
<div class="flcd-hero__title">FOSSLight<br>Community Day <span class="flcd-grad">#6</span></div>
<p class="flcd-hero__dek">Scanner와 Hub의 새로운 기능부터 글로벌 SBOM 규제, 현장의 활용기까지. 오픈소스 관리의 오늘을 함께 나눈 하루.</p>
<div class="flcd-facts"><div class="flcd-fact"><span>Date</span><b>2026.10.28 (수)</b></div><div class="flcd-fact"><span>Venue</span><b>서울 서초구</b></div><div class="flcd-fact"><span>Program</span><b>Talk · Demo · Q&amp;A</b></div></div>
</div>

</div>
<div class="flcd-sec">
<div class="flcd-eyebrow">Key Takeaways</div>
<h2 class="flcd-h2" id="key-takeaways">한눈에 보는 핵심 포인트</h2>
<div class="flcd-takeaways">
<div class="flcd-take"><span class="flcd-take__no">01</span><h3 class="flcd-take__title">Scanner, 더 가볍고 넓게</h3><p class="flcd-take__text">폴더 단위 결과 요약과 분석 속도 개선, uv.lock·NuGet CPM·Gradle 9 대응, CycloneDX 1.6·SPDX 2.3 출력에 설치 파일 하나로 쓰는 Windows GUI까지 더해졌습니다.</p></div>
<div class="flcd-take"><span class="flcd-take__no">02</span><h3 class="flcd-take__title">SBOM, 이제는 규제</h3><p class="flcd-take__text">EU CRA, 미국 FD&amp;C Act §524B 등 SBOM이 법적 의무로 자리 잡는 흐름과 VEX, 제조사의 대응 과제를 짚었습니다.</p></div>
<div class="flcd-take"><span class="flcd-take__no">03</span><h3 class="flcd-take__title">NVD를 넘어 OSV까지</h3><p class="flcd-take__text">FOSSLight Hub가 OSV 데이터를 연계해 CVE가 없는 오픈소스 취약점까지 식별합니다. VEX 지원도 준비하고 있습니다.</p></div>
<div class="flcd-take"><span class="flcd-take__no">04</span><h3 class="flcd-take__title">현장에서 배우는 FOSSLight</h3><p class="flcd-take__text">ETRI의 FOSSLight 기반 컴플라이언스 시스템(OLA) 활용기와 Scanner·Hub Q&amp;A로 실무 노하우를 나눴습니다.</p></div>
</div>
</div>
<div class="flcd-sec" markdown="1">
<div class="flcd-eyebrow">Sessions</div>
<h2 class="flcd-h2" id="sessions">세션 다시 보기</h2>
<p class="flcd-lede">카드마다 발표자료(PDF)를 바로 확인할 수 있습니다.</p>
<div class="flcd-grid" markdown="1">
<div class="flcd-card" markdown="1">

![FOSSLight Scanner 또 Update 되었어요 발표 현장](../../assets/img/news/2510/20261028_130104.jpg)

<div class="flcd-card__body"><span class="flcd-tag flcd-tag--update">UPDATE</span><h3 class="flcd-card__title">FOSSLight Scanner 또 Update 되었어요</h3><div class="flcd-speaker"><span class="flcd-avatar">박</span><span><b>박원재</b><small>LG전자</small></span></div><p class="flcd-card__desc">파일별 결과의 폴더 단위 요약, Source 분석 속도와 외부 조회 안정성 개선, uv.lock·NuGet CPM·Gradle 9 대응, JAR 분석 강화, SBOM 출력 확장까지 최근 업데이트를 정리했습니다.</p></div>

[발표자료 보기 →](../../assets/files/261028/261028_FL_Day_FOSSLightScanner또Update되었어요_박원재.pdf)

</div>
<div class="flcd-card" markdown="1">

![예쁘고 쉬운 UI를 입힌 FOSSLight Scanner 발표 현장](../../assets/img/news/2510/20261028_132049.jpg)

<div class="flcd-card__body"><span class="flcd-tag flcd-tag--talk">TALK</span><h3 class="flcd-card__title">예쁘고 쉬운 UI를 입힌 FOSSLight Scanner</h3><div class="flcd-speaker"><span class="flcd-avatar">방</span><span><b>방재권</b><small>LG전자</small></span></div><p class="flcd-card__desc">Python 설치나 명령어 없이 설치 파일 하나로 쓰는 Windows용 FOSSLight Scanner GUI를 소개하고, New Scan부터 Overview, 라이선스 위험도 확인까지 직접 시연했습니다.</p></div>

[발표자료 보기 →](../../assets/files/261028/261028_FL_Day_예쁘고쉬운UI를입힌FOSSLightScanner_방재권.pdf)

</div>
<div class="flcd-card" markdown="1">

![변화하는 SBOM 규제와 트렌드 발표 현장](../../assets/img/news/2510/20261028_134924.jpg)

<div class="flcd-card__body"><span class="flcd-tag flcd-tag--talk">TALK</span><h3 class="flcd-card__title">변화하는 SBOM 규제와 트렌드</h3><div class="flcd-speaker"><span class="flcd-avatar">오</span><span><b>오혜진</b><small>LG전자 SW Security Governance팀</small></span></div><p class="flcd-card__desc">SBOM의 개념과 필요성에서 출발해 미국·EU·한국 등의 규제 동향과 SBOM·VEX의 관계, 현재의 한계점, 제조사의 대응 과제를 살펴봤습니다.</p></div>

[발표자료 보기 →](../../assets/files/261028/261028_FL_Day_변화하는SBOM규제와트렌드_오혜진.pdf)

</div>
<div class="flcd-card" markdown="1">

![FOSSLight Hub의 강화된 보안 취약점 검출 능력 발표 현장](../../assets/img/news/2510/20261028_142746.jpg)

<div class="flcd-card__body"><span class="flcd-tag flcd-tag--talk">TALK</span><h3 class="flcd-card__title">FOSSLight Hub의 강화된 보안 취약점 검출 능력</h3><div class="flcd-speaker"><span class="flcd-avatar">최</span><span><b>최혜성</b><small>LG전자</small></span></div><p class="flcd-card__desc">NVD 중심 조회를 넘어 OSV 데이터까지 연계한 SBOM 기반 취약점 관리 구조와 메뉴별 확인 방법, 향후 VEX 지원 계획을 소개했습니다.</p></div>

[발표자료 보기 →](../../assets/files/261028/261028_FL_Day_FOSSLightHub의강화된보안취약점검출능력_최혜성.pdf)

</div>
<div class="flcd-card" markdown="1">

![FOSSLight 사용자 경험을 공유합니다 발표 현장](../../assets/img/news/2510/20261028_150238.jpg)

<div class="flcd-card__body"><span class="flcd-tag flcd-tag--talk">TALK</span><h3 class="flcd-card__title">FOSSLight 사용자 경험을 공유합니다</h3><div class="flcd-speaker"><span class="flcd-avatar">엄</span><span><b>엄숭광</b><small>ETRI</small></span></div><p class="flcd-card__desc">ETRI의 오픈소스 컴플라이언스 제도와 프로세스, 그리고 FOSSLight 1.0을 기반으로 개발한 오픈소스 컴플라이언스 시스템(OLA) 활용기를 공유했습니다.</p></div>

[발표자료 보기 →](../../assets/files/261028/261028_FL_Day_FOSSLight사용자경험을공유합니다_엄숭광.pdf)

</div>
<div class="flcd-card" markdown="1">
<div class="flcd-term" role="img" aria-label="FOSSLight Scanner FAQ 질문 목록"><div class="flcd-term__bar"><i></i><i></i><i></i><span>scanner-faq.md</span></div><div class="flcd-term__body"><div><em>Q1</em>어떤 Scanner를 써야 하나요?</div><div><em>Q2</em>분석은 제대로 끝났나요?</div><div><em>Q3</em>예상한 OSS가 왜 검출되지 않나요?</div><div><em>Q4</em>Scanner마다 결과가 왜 다른가요?</div><div><em>Q5</em>결과를 그대로 써도 되나요?</div></div></div>
<div class="flcd-card__body"><span class="flcd-tag flcd-tag--ama">AMA</span><h3 class="flcd-card__title">무엇이든 물어보세요, FOSSLight Scanner 편</h3><div class="flcd-speaker"><span class="flcd-avatar">정</span><span><b>정우철</b><small>LG전자</small></span></div><p class="flcd-card__desc">어떤 Scanner를 써야 하는지, 분석이 제대로 끝났는지 확인하는 법, OSS가 검출되지 않거나 Scanner마다 결과가 다른 이유까지 자주 묻는 질문에 답했습니다.</p></div>

[발표자료 보기 →](../../assets/files/261028/261028_FL_Day_무엇이든물어보세요_FOSSLightScanner편_정우철.pdf)

</div>
<div class="flcd-card" markdown="1">

![무엇이든 물어보세요, FOSSLight Hub 편 현장](../../assets/img/news/2510/20261028_1.jpg)

<div class="flcd-card__body"><span class="flcd-tag flcd-tag--ama">AMA</span><h3 class="flcd-card__title">무엇이든 물어보세요, FOSSLight Hub 편</h3><div class="flcd-speaker"><span class="flcd-avatar">민</span><span><b>민경선</b><small>LG전자</small></span></div><p class="flcd-card__desc">취약점이 있는 오픈소스를 쓰는 프로젝트 찾기, 취약점 알림 메일, Review Report, SBOM Compare·Export, API 활용까지 FOSSLight Hub에서 자주 묻는 기능을 정리했습니다.</p></div>

[발표자료 보기 →](../../assets/files/261028/261028_FL_Day_무엇이든물어보세요_FOSSLightHub편_민경선.pdf)

</div>
<div class="flcd-card" markdown="1">

![FOSSLight Enterprise를 경험해보세요 발표 현장](../../assets/img/news/2510/20261028_161341.jpg)

<div class="flcd-card__body"><span class="flcd-tag flcd-tag--talk">TALK</span><h3 class="flcd-card__title">FOSSLight Enterprise를 경험해보세요</h3><div class="flcd-speaker"><span class="flcd-avatar">김</span><span><b>김경애</b><small>LG전자</small></span></div><p class="flcd-card__desc">SaaS·DB 구독과 CoReviewer 플러그인 등 FOSSLight Scanner·Hub Enterprise의 제공 방식과 주요 기능, 활용 방안을 소개했습니다.</p></div>

[발표자료 보기 →](../../assets/files/261028/261028_FL_Day_FOSSLightEnterprise를경험해보세요_김경애.pdf)

</div>
</div>
</div>
<div class="flcd-sec flcd-thanks" markdown="1">
<div class="flcd-eyebrow">Thank You</div>
<h2 class="flcd-h2" id="thank-you">함께해 주셔서 감사합니다</h2>

발표를 준비해 주신 연사분들과 현장을 찾아 주신 모든 분께 감사드립니다. 다음 FOSSLight Community Day에서 다시 만나요!

<div class="flcd-partners"><span>Venue Partners · 장소 후원</span><b>NIPA 정보통신산업진흥원</b><b>OpenUp</b></div>
<div class="flcd-ctas"><a class="flcd-btn flcd-btn--primary" href="https://github.com/fosslight" target="_blank" rel="noopener noreferrer">GitHub에서 FOSSLight 만나기 ↗</a><a class="flcd-btn" href="https://fosslight.org/fosslight-guide/">FOSSLight 가이드 보기 →</a></div>

</div>
</div>
