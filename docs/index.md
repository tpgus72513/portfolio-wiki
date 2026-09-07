---
title: 권세현 기술 포트폴리오
summary: 프로젝트에서 내린 기술적 결정과 문제 해결 과정을 정리한 권세현의 공개 포트폴리오입니다.
type: knowledge
tags:
  - portfolio
  - projects
status: published
created: 2026-08-24
updated: 2026-09-07
hide:
  - navigation
  - toc
---

<div class="portfolio-hero" markdown>

<div class="portfolio-hero__copy" markdown>

<p class="portfolio-eyebrow">BUILD LOG · BACKEND & SOFTWARE</p>

# 문제를 구조화하고,<br>끝까지 구현합니다.

백엔드를 중심으로 웹 서비스와 AI 기능을 연결하고 있습니다. 결과만 나열하지 않고, 문제를 정의한 기준과 기술적 선택, 검증 과정까지 기록합니다.

[대표 프로젝트 보기](#selected-work){ .md-button .md-button--primary }
[GitHub 방문하기](https://github.com/tpgus72513){ .md-button }

</div>

<aside class="hero-log" aria-label="포트폴리오 방향">
  <header class="hero-log__header">
    <span class="hero-log__signal"></span>
    <span>portfolio.status</span>
  </header>
  <ul class="hero-log__body">
    <li class="hero-log__row"><span>Focus</span><strong>Backend · AI integration</strong></li>
    <li class="hero-log__row"><span>Practice</span><strong>Plan · Build · Verify</strong></li>
    <li class="hero-log__row"><span>Archive</span><strong>Selected project cases</strong></li>
  </ul>
  <footer class="hero-log__footer">main / continuously shipped</footer>
</aside>

</div>

<div class="portfolio-section-heading" id="selected-work">
  <p class="portfolio-eyebrow">SELECTED WORK</p>
  <h2>대표 프로젝트</h2>
  <p>내가 맡은 역할과 판단 근거를 확인할 수 있는 프로젝트입니다.</p>
</div>

<div class="project-grid" markdown>

<article class="project-card" markdown>

<div class="project-card__meta"><span>01</span><span>Frontend · Team</span></div>

### [세종페이(PAYUS)](projects/sejong-pay.md)

캠퍼스와 지역 상권을 연결하는 QR 간편결제 MVP입니다. 화면 구조와 결제 흐름을 연결하고, 삭제된 프론트엔드 소스 46개를 Git 이력에서 복구했습니다.

<div class="project-tags"><span>React</span><span>QR Flow</span><span>Git Recovery</span></div>

[사례 읽기 →](projects/sejong-pay.md){ .project-card__link }

</article>

<article class="project-card" markdown>

<div class="project-card__meta"><span>02</span><span>Backend · Team Lead</span></div>

### [올클(AllCle)](projects/ticketing-simulator.md)

고수요 티켓팅 과정을 반복해서 연습할 수 있도록 1인 시뮬레이터로 단순화했습니다. 상태 변화와 매진 조건을 예측 가능한 규칙으로 설계했습니다.

<div class="project-tags"><span>Backend</span><span>Simulation</span><span>Planning</span></div>

[사례 읽기 →](projects/ticketing-simulator.md){ .project-card__link }

</article>

<article class="project-card" markdown>

<div class="project-card__meta"><span>03</span><span>Full Stack · Solo</span></div>

### [다이내믹 뷰티 큐레이터](projects/dynamic-beauty-curator.md)

개인의 피부 정보와 위치별 환경 데이터를 결합해 스킨케어 루틴을 추천했습니다. 모델 연동과 외부 API 장애에 대응하는 대체 경로를 설계했습니다.

<div class="project-tags"><span>Recommendation</span><span>API</span><span>Fallback</span></div>

[사례 읽기 →](projects/dynamic-beauty-curator.md){ .project-card__link }

</article>

<article class="project-card" markdown>

<div class="project-card__meta"><span>04</span><span>AI Recommendation · Team</span></div>

### [소상공인 상권 분석·마케팅 지원](projects/ai-mentoring-internship.md)

상권 분석 결과를 실제 마케팅 문구로 연결했습니다. 생성 결과의 과장 표현을 검사하고, AI 장애 시 규칙 기반 결과를 제공하도록 구성했습니다.

<div class="project-tags"><span>AI</span><span>Content</span><span>Fallback</span></div>

[사례 읽기 →](projects/ai-mentoring-internship.md){ .project-card__link }

</article>

</div>

<div class="portfolio-section-heading portfolio-section-heading--compact">
  <p class="portfolio-eyebrow">ENGINEERING NOTES</p>
  <h2>무엇을 기록하는가</h2>
</div>

<div class="record-grid">
  <div class="record-item">
    <strong>01 · Decision</strong>
    <span>무엇을 만들었는지보다 왜 그 범위를 선택했는지 기록합니다.</span>
  </div>
  <div class="record-item">
    <strong>02 · Troubleshooting</strong>
    <span>막힌 지점, 원인 추적 과정과 해결하지 못한 한계도 남깁니다.</span>
  </div>
  <div class="record-item">
    <strong>03 · Verification</strong>
    <span>직접 실행한 검증과 다음 개선 방향을 구분해 정리합니다.</span>
  </div>
</div>
