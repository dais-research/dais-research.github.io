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

        ### Undergraduate Researchers

        <div class="grid gap-8 md:grid-cols-3 mt-6">
          <div class="text-center">
            <img src="/media/authors/hyoeun.webp" alt="Hyoeun Choi"
                 class="rounded-full w-40 h-40 object-cover mx-auto mb-4 shadow-md" />
            <h4 class="text-xl font-semibold mb-1">Hyoeun Choi</h4>
            <p class="text-sm opacity-75 mb-2">Research Intern</p>
            <p class="text-sm">
              Chungnam National University<br/>
              Spring 2026<br/>
              <span class="opacity-75">Computer vision · XAI</span>
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
      subtitle: 'DASFAA 2026 · Jeju Island, South Korea'
      text: |-
        <div class="grid gap-4 md:grid-cols-2 mt-6">
          <a href="/gallery/">
            <img src="/media/gallery/dasfaa2026-pi.webp"
                 alt="DASFAA 2026 conference"
                 class="rounded-lg shadow-md object-cover w-full h-64" />
          </a>
          <a href="/gallery/">
            <img src="/media/gallery/dasfaa2026-reception.webp"
                 alt="DASFAA 2026 reception"
                 class="rounded-lg shadow-md object-cover w-full h-64" />
          </a>
        </div>

        <p class="mt-4 text-center">
          <a href="/gallery/" class="underline">View full gallery →</a>
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

        <a href="mailto:woongheelee&#64;kier&#46;re&#46;kr" class="inline-flex items-center gap-1 underline">Send email ↗</a>
    design:
      columns: '1'
---
