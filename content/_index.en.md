---
title: ''
summary: ''
date: 2026-05-06
type: landing

sections:
  # ─────────────────────────────────────────────────────────────────────────
  # ABOUT THE GROUP (landing hero)
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: about
    content:
      title: 'DAIS Research Group'
      subtitle: 'Data · Analysis · Intelligence · System'
      text: |-
        The **DAIS Research Group** is an AI and data science research group within
        the Energy Platform Research Laboratory at the Korea Institute of
        Energy Research (KIER). We use complex, real-world data from energy and
        scientific research as both a starting point and a testbed for studying
        generalizable AI methodologies, including machine learning, scientific
        document understanding, knowledge-based reasoning, and AI agents. Rather
        than building one-off solutions for individual projects, we develop models,
        evaluation methods, and data-processing pipelines that can transfer across
        scientific and industrial domains, connecting methodological advances with
        academic contributions and practical research tools.

        ### Data → Analysis → Intelligence → System

        - **D — Data.** Collecting and organizing the diverse research data that
          arises in the field — unstructured documents (PDFs, reports, papers),
          experimental and process measurements, and more.
        - **A — Analysis.** Structure analysis and information extraction from
          documents; preprocessing of experimental and process data into shapes
          downstream models can use.
        - **I — Intelligence.** Classification, summarization, search, and
          recommendation over large document and data collections; prediction and
          fitting models for experimental and process data; robust learning methods
          combined with domain knowledge.
        - **S — System.** Turning models and analyses into things other people can
          actually use; automating repetitive work and keeping analysis code
          reproducible.

        We collaborate with other groups within KIER and with external partners,
        organizing our work as reusable code and workflows rather than one-off
        solutions tied to a single project.
    design:
      columns: '1'

  # ─────────────────────────────────────────────────────────────────────────
  # NEWS (awards, paper acceptances; newest first)
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: news
    content:
      title: 'Group News'
      subtitle: ''
      text: |-
        <p class="text-sm font-semibold opacity-60 mb-3">November 6, 2026</p>

        <div class="grid gap-8 md:grid-cols-2 items-center">
          <div>
            <figure>
              <img src="/media/gallery/ack2026-award.webp"
                   alt="Yunyeong Ju holding the award certificate in front of the ACK 2026 banner"
                   class="rounded-lg shadow-md w-full" />
              <figcaption class="text-xs text-center mt-2 opacity-75">
                After the ACK 2026 award — Yunyeong Ju
              </figcaption>
            </figure>
          </div>
          <div>
            <p class="text-xl font-semibold mb-3">🏆 Industry-Academia-Research Collaboration Excellence Award</p>
            <p class="mb-2">
              <strong>Best Paper Award</strong><br/>
              ACK 2026 (Annual Conference of KIPS, Korea Information Processing Society)<br/>
              <span class="opacity-75">November 6, 2026, Seoul, South Korea</span>
            </p>
            <p class="mb-2">
              Awardees: <strong>Yunyeong Ju</strong> (Korea University of Technology and Education, research intern),
              Seungyeon Jang, Soohyun Kim, Woonghee Lee (Korea Institute of Energy Research)
            </p>
            <p class="text-sm opacity-90">
              Paper: <em>Brightness-Band Projection for Residual Silicon Segmentation in C/SiC Composites</em>
              <span class="opacity-75">(in Korean)</span>
            </p>
            <p class="mt-3">
              <a href="/publications/ack2026-csic-si-seg/" class="underline">View paper →</a>
            </p>
          </div>
        </div>

        <hr class="my-10 opacity-20" />

        <p class="text-sm font-semibold opacity-60 mb-2">May 21, 2026</p>

        <p class="mb-1">
          🏆 <strong>Bronze Award</strong> — Undergraduate / High-School Paper
          Competition at ASK 2026 (Annual Symposium of the Korea Information
          Processing Society, Gangneung).
          Awardee <strong>Hyoeun Choi</strong> (Chungnam National University, research intern).
        </p>
        <p class="text-sm opacity-90">
          Paper: <em>Comparing SHAP and CRAFT Across Architectures for PEMFC SEM Images</em>
          · <a href="/publications/kips2026-shap-craft/" class="underline">View paper →</a>
        </p>
    design:
      columns: '1'

  # ─────────────────────────────────────────────────────────────────────────
  # PUBLICATIONS (placeholder — populated as work appears)
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: publications
    content:
      title: 'Publications'
      subtitle: ''
      text: ''
    design:
      columns: '1'

  - block: collection
    id: pub-conference
    content:
      title: 'Domestic Conference Papers'
      filters:
        folders:
          - publications
        publication_type: 'paper-conference'
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: pub-software
    content:
      title: 'Software Copyrights'
      filters:
        folders:
          - publications
        publication_type: 'software'
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: pub-media
    content:
      title: 'Media & Outreach'
      filters:
        folders:
          - publications
        publication_type: 'article-magazine'
        exclude_featured: false
    design:
      view: citation

  # ─────────────────────────────────────────────────────────────────────────
  # MEMBERS
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: members
    content:
      title: 'Members'
      subtitle: ''
      text: |-
        ### Principal Investigator

        <div class="grid gap-8 md:grid-cols-3 mt-6 mb-12">
          <div class="text-center">
            <img src="/media/authors/woongheelee.webp" alt="Woonghee Lee"
                 class="rounded-full w-40 h-40 object-cover mx-auto mb-4 shadow-md" />
            <h4 class="text-xl font-semibold mb-1">Woonghee Lee, Ph.D.</h4>
            <p class="text-sm opacity-75 mb-2">Senior Researcher</p>
            <p class="text-sm">
              Energy Platform Research Lab., KIER
            </p>
            <p class="text-sm mt-2">
              <a href="mailto:woongheelee&#64;kier&#46;re&#46;kr">Email</a> ·
              <a href="https://woongheelee.github.io/" target="_blank" rel="noopener">CV ↗</a>
            </p>
          </div>
        </div>

        ### Undergraduate Interns

        <div class="grid gap-8 md:grid-cols-3 mt-6 mb-12">
          <div class="text-center">
            <img src="/media/authors/yunyeong.webp" alt="Yunyeong Ju"
                 class="rounded-full w-40 h-40 object-cover mx-auto mb-4 shadow-md" />
            <h4 class="text-xl font-semibold mb-1">Yunyeong Ju</h4>
            <p class="text-sm opacity-75 mb-2">Research Intern (2026-07 – 2026-12)</p>
            <p class="text-sm">
              Korea University of Technology and Education (KOREATECH)<br/>
              <span class="opacity-75">Computer Vision</span>
            </p>
            <p class="text-sm mt-2">
              <a href="https://github.com/dragonju02" target="_blank" rel="noopener"
                 class="hover:underline">GitHub ↗</a>
            </p>
          </div>

          <div class="text-center">
            <img src="/media/authors/dongwan.webp" alt="Dongwan Yoo"
                 class="rounded-full w-40 h-40 object-cover mx-auto mb-4 shadow-md" />
            <h4 class="text-xl font-semibold mb-1">Dongwan Yoo</h4>
            <p class="text-sm opacity-75 mb-2">Research Intern (2026-07 – 2026-12)</p>
            <p class="text-sm">
              Chungnam National University<br/>
              <span class="opacity-75">LLM Architecture · Machine Unlearning</span>
            </p>
            <p class="text-sm mt-2">
              <a href="https://github.com/peradura" target="_blank" rel="noopener"
                 class="hover:underline">GitHub ↗</a>
            </p>
          </div>
        </div>

        ### Alumni

        <div class="grid gap-8 md:grid-cols-3 mt-6">
          <div class="text-center">
            <img src="/media/authors/hyoeun.webp" alt="Hyoeun Choi"
                 class="rounded-full w-40 h-40 object-cover mx-auto mb-4 shadow-md" />
            <h4 class="text-xl font-semibold mb-1">Hyoeun Choi</h4>
            <p class="text-sm opacity-75 mb-2">Research Intern (2026-03 – 2026-06)</p>
            <p class="text-sm">
              Chungnam National University<br/>
              <span class="opacity-75">Computer vision · XAI</span>
            </p>
            <p class="text-sm mt-2 opacity-75">
              Bronze Award, ASK 2026 Undergraduate / High-School Paper Competition
            </p>
            <p class="text-sm mt-2">
              <a href="https://github.com/hekengi" target="_blank" rel="noopener">GitHub ↗</a>
            </p>
          </div>
        </div>

    design:
      columns: '1'

  # ─────────────────────────────────────────────────────────────────────────
  # GALLERY TEASER
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    content:
      title: 'Gallery'
      subtitle: ''
      text: |-
        ### ACK 2026 — Seoul, South Korea · November 2026

        <figure class="mt-4">
          <img src="/media/gallery/ack2026-group.webp"
               alt="Yunyeong Ju, Woonghee Lee, and Dongwan Yoo in front of the ACK 2026 banner"
               class="rounded-lg shadow-md w-full" />
          <figcaption class="text-xs text-center mt-2 opacity-75">
            From left: Yunyeong Ju, Woonghee Lee, and Dongwan Yoo
          </figcaption>
        </figure>

        <p class="mt-6 text-right">
          <a href="/en/gallery/" class="underline">View the full gallery →</a>
        </p>
    design:
      columns: '1'

  # ─────────────────────────────────────────────────────────────────────────
  # CONTACT
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        152 Gajeong-ro, Yuseong-gu, Daejeon 34129, South Korea

        <p>
        <a href="mailto:woongheelee&#64;kier&#46;re&#46;kr" class="inline-flex items-center gap-1 underline">Send email ↗</a>
        <span class="mx-2 opacity-60" aria-hidden="true">·</span>
        <a href="https://calendar.google.com/calendar/embed?src=gongdol2pooh%40gmail.com&ctz=Asia%2FSeoul" target="_blank" rel="noopener" class="inline-flex items-center gap-1 underline">View meeting availability ↗</a>
        </p>

        For meetings or collaboration discussions, please contact us by email.
    design:
      columns: '1'
---
