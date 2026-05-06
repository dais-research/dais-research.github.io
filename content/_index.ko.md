---
title: ''
summary: ''
date: 2026-05-06
type: landing

sections:
  # ─────────────────────────────────────────────────────────────────────────
  # HERO / About-the-PI
  # ─────────────────────────────────────────────────────────────────────────
  - block: resume-biography-3
    id: about
    content:
      username: woongheelee
      text: |-
        **DAIS 연구 그룹**은 이미지·신호·텍스트·시계열 등 이질적인 연구
        데이터를 다루는 기계학습 방법을 연구하며, 에너지·소재 분야의 데이터를
        위한 AI 방법론, 시계열 및 문서 분석, 강건한 모델 학습, 연구용 AI
        에이전트 등에 관심을 두고 있습니다.

        **학력**
        - Postdoc · 한양대학교 ERICA (2023.03 – 2024.07)
        - Ph.D. 컴퓨터공학 · 한양대학교 (2023.02)
        - Visiting Scholar · Kennesaw State University, USA (2021.07 – 2022.01)
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # ─────────────────────────────────────────────────────────────────────────
  # ABOUT THE GROUP
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    content:
      title: '연구 그룹 소개'
      subtitle: 'Data → Intelligence → System'
      text: |-
        **DAIS 연구 그룹**은 한국에너지기술연구원(KIER) 에너지AI·계산과학실 산하의 연구
        그룹으로, 에너지 분야의 연구 현장에서 발생하는 다양한 형태의 데이터를 다루기 위한
        AI 방법론을 개발합니다. 도메인에 종속되지 않고 여러 과제에서 공통적으로 활용할 수
        있는 분석 도구와 데이터 처리 파이프라인을 설계·구현하는 것을 지향합니다.

        ### 전문 분야

        과제 수행 과정에서 주로 AI·데이터 기반 분석 및 자동화 업무를 담당하고 있으며,
        실험·정책·행정 등 서로 다른 성격의 과제에서 공통적으로 활용 가능한 분석 도구와
        데이터 처리 파이프라인의 설계·구현을 수행하고 있습니다.

        - 비정형 문서(PDF, 보고서, 논문 등)의 구조 분석 및 핵심 정보 추출
        - 대규모 문서·데이터에 대한 분류, 요약, 검색, 추천을 위한 모델링
        - 실험·공정 데이터 전처리 및 예측·피팅 모델 구현
        - 반복 업무의 자동화 및 재현 가능한 분석 코드 정리

        개별 과제에 국한되지 않고, 다른 과제에서도 재사용 가능한 코드와 워크플로우 형태로
        정리하는 것을 지향합니다.
    design:
      columns: '1'

  # ─────────────────────────────────────────────────────────────────────────
  # MEMBERS
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: members
    content:
      title: '구성원'
      subtitle: ''
      text: |-
        ### Principal Investigator (PI)

        <div class="grid gap-8 md:grid-cols-3 mt-6 mb-12">
          <div class="text-center">
            <img src="/media/authors/woongheelee.webp" alt="이웅희"
                 class="rounded-full w-40 h-40 object-cover mx-auto mb-4 shadow-md" />
            <h4 class="text-xl font-semibold mb-1">이웅희 (Woonghee Lee), Ph.D.</h4>
            <p class="text-sm opacity-75 mb-2">선임연구원</p>
            <p class="text-sm">
              한국에너지기술연구원<br/>
              에너지AI·계산과학실<br/>
              <a href="mailto:woongheelee&#64;kier&#46;re&#46;kr">메일 보내기</a>
            </p>
          </div>
        </div>

        ### 학부 연구생

        <div class="grid gap-8 md:grid-cols-3 mt-6">
          <div class="text-center">
            <img src="/media/authors/hyoeun.webp" alt="최효은"
                 class="rounded-full w-40 h-40 object-cover mx-auto mb-4 shadow-md" />
            <h4 class="text-xl font-semibold mb-1">최효은 (Hyoeun Choi)</h4>
            <p class="text-sm opacity-75 mb-2">학부 인턴</p>
            <p class="text-sm">
              충남대학교 컴퓨터융합학부<br/>
              백마인턴십 · 2026년 1학기<br/>
              <span class="opacity-75">컴퓨터 비전 · XAI</span>
            </p>
          </div>
        </div>

    design:
      columns: '1'

  # ─────────────────────────────────────────────────────────────────────────
  # PUBLICATIONS
  # ─────────────────────────────────────────────────────────────────────────
  # ─────────────────────────────────────────────────────────────────────────
  # PROJECTS
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: projects
    content:
      title: '참여 연구 과제'
      subtitle: '현재 진행 중'
      text: |-
        - 소재-공정 전주기 데이터 HUB 및 지능형 연구 설계 기반의 고성능 리튬 이차 전지 구현
        - AI 탐색설계 및 전주기 데이터 관리 기반 우주발사체용 초고온 내열 세라믹 소재 HUB 구축
        - 청정수소 기술개발 정책지원 및 네트워크 기반 구축
        - 에너지 비용 15% 절감 건물·에너지 산업공정 설비 자율운전 국산 AI 에이전트 개발
        - 에너지 R&D 초융합을 위한 AI·계산과학 연구 체계 고도화
        - 에너지 플랜트 운전 효율성 향상을 위한 통합 AI 예측 시스템 개발
        - 배터리 제조공정 최적화를 위한 비접촉 초저함수율 측정 기술
        - 배터리 제조공정의 전주기 에너지 효율 솔루션 기술
        - AI 기반 에너지 소재 열화 예측 플랫폼 구축을 위한 첨단 분석 데이터 인프라 개발
    design:
      columns: '1'

  - block: markdown
    id: publications
    content:
      title: '연구 성과'
      subtitle: ''
      text: ''
    design:
      columns: '1'

  - block: collection
    content:
      title: '국내 학술대회'
      filters:
        folders:
          - publications
        publication_type: 'paper-conference'
        exclude_featured: false
    design:
      view: citation

  - block: collection
    content:
      title: '소프트웨어 저작권'
      filters:
        folders:
          - publications
        publication_type: 'software'
        exclude_featured: false
    design:
      view: citation

  # ─────────────────────────────────────────────────────────────────────────
  # GALLERY TEASER
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    content:
      title: '갤러리'
      subtitle: 'DASFAA 2026 · 제주'
      text: |-
        <div class="grid gap-4 md:grid-cols-2 mt-6">
          <a href="/gallery/">
            <img src="/media/gallery/dasfaa2026-pi.webp"
                 alt="DASFAA 2026 학회장"
                 class="rounded-lg shadow-md object-cover w-full h-64" />
          </a>
          <a href="/gallery/">
            <img src="/media/gallery/dasfaa2026-reception.webp"
                 alt="DASFAA 2026 리셉션"
                 class="rounded-lg shadow-md object-cover w-full h-64" />
          </a>
        </div>

        <p class="mt-4 text-center">
          <a href="/gallery/" class="underline">갤러리 전체 보기 →</a>
        </p>
    design:
      columns: '1'

  # ─────────────────────────────────────────────────────────────────────────
  # CONTACT
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: contact
    content:
      title: '연락처 · 합류 안내'
      subtitle: ''
      text: |-
        학연생 및 학부 인턴으로 합류하고 싶은 분들의 연락을 환영합니다.

        대전광역시 유성구 가정로 152 (34129)

        E-mail: <a href="mailto:woongheelee&#64;kier&#46;re&#46;kr">메일 보내기</a>
    design:
      columns: '1'
---
