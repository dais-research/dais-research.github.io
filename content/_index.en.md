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
        The **DAIS Research Group** is a research group within the Energy AI &
        Computational Science Lab. at the Korea Institute of Energy Research (KIER).
        We develop AI methods for the heterogeneous data that arises in energy
        research — aiming for tools and pipelines that can be reused across projects
        rather than tied to a single domain or dataset.

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
  # AWARDS / RECOGNITION
  # ─────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: awards
    content:
      title: 'Recent Award'
      subtitle: ''
      text: |-
        <div class="grid gap-8 md:grid-cols-2 mt-6 items-center">
          <div>
            <figure>
              <img src="/media/gallery/ask2026-award.webp"
                   alt="Hyoeun Choi and Woonghee Lee at the ASK 2026 award ceremony"
                   class="rounded-lg shadow-md w-full" />
              <figcaption class="text-xs text-center mt-2 opacity-75">
                After the ASK 2026 award ceremony
              </figcaption>
            </figure>
          </div>
          <div>
            <p class="text-xl font-semibold mb-3">🏆 Bronze Award</p>
            <p class="mb-2">
              <strong>Undergraduate / High-School Paper Competition</strong><br/>
              ASK 2026 (Annual Symposium of the Korea Information Processing Society)<br/>
              <span class="opacity-75">May 21, 2026, Gangneung, South Korea</span>
            </p>
            <p class="mb-2">
              Awardee: <strong>Hyoeun Choi</strong> (Chungnam National University, research intern)
            </p>
            <p class="text-sm opacity-90">
              Paper: <em>Comparing SHAP and CRAFT Across Architectures for PEMFC SEM Images</em>
            </p>
            <p class="mt-3">
              <a href="/publications/kips2026-shap-craft/" class="underline">View paper →</a>
            </p>
          </div>
        </div>
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
              Energy AI &amp; Computational Science Lab., KIER
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
        ### ASK 2026 — Gangneung · May 2026

        <div class="grid gap-4 md:grid-cols-2 mt-4 mb-10">
          <figure>
            <img src="/media/gallery/ask2026-award.webp"
                 alt="ASK 2026 award ceremony"
                 class="rounded-lg shadow-md w-full bg-white" />
            <figcaption class="text-xs text-center mt-2 opacity-75">
              After the ASK 2026 award ceremony
            </figcaption>
          </figure>
          <figure>
            <img src="/media/gallery/ask2026-certificate.webp"
                 alt="ASK 2026 Bronze Award certificate"
                 class="rounded-lg shadow-md w-full bg-white" />
            <figcaption class="text-xs text-center mt-2 opacity-75">
              Bronze Award certificate — Undergraduate / High-School Paper Competition
            </figcaption>
          </figure>
        </div>

        ### DASFAA 2026 — Jeju Island · April 2026

        <div class="grid gap-4 md:grid-cols-2 mt-4">
          <figure>
            <img src="/media/gallery/dasfaa2026-pi.webp"
                 alt="Woonghee Lee at DASFAA 2026 welcome banner"
                 class="rounded-lg shadow-md w-full" />
            <figcaption class="text-xs text-center mt-2 opacity-75">
              At the DASFAA 2026 welcome banner
            </figcaption>
          </figure>
          <figure>
            <img src="/media/gallery/dasfaa2026-reception.webp"
                 alt="DAIS at the DASFAA 2026 outdoor reception"
                 class="rounded-lg shadow-md w-full" />
            <figcaption class="text-xs text-center mt-2 opacity-75">
              DAIS at the conference reception
            </figcaption>
          </figure>
        </div>
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

        <a href="mailto:woongheelee&#64;kier&#46;re&#46;kr" class="inline-flex items-center gap-1 underline">Send email ↗</a>
    design:
      columns: '1'
---
