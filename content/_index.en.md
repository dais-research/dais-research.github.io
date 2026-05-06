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
        The **DAIS Research Group** applies machine learning to image, signal,
        text, and time-series data — focused on AI methods for energy and
        materials research, including time-series and document analysis,
        robust model training, and AI agents for research workflows.

        **Education**
        - Postdoctoral Researcher · Hanyang University ERICA (Mar 2023 – Jul 2024)
        - Ph.D., Computer Science & Engineering · Hanyang University (Feb 2023)
        - Visiting Scholar · Kennesaw State University, USA (Jul 2021 – Jan 2022)
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
      title: 'About DAIS'
      subtitle: 'Data → Intelligence → System'
      text: |-
        **DAIS Research Group** at the Korea Institute of Energy Research (KIER) develops
        domain-agnostic AI methods for energy and materials research. We collect, analyze,
        and model heterogeneous research data — microscopy images, spectra, experimental
        tables, and scientific documents — and turn the resulting models into deployable
        services.

        Our work is organized around three pillars:

        - **D-A — Data & Analysis.** Microscopy preprocessing, spectrum parsing,
          PDF/HTML document parsing, and time-series cleaning. The plumbing that makes
          downstream modeling possible.
        - **I — Intelligence.** Image segmentation, time-series and tabular models,
          Bayesian optimization, physics-informed networks, and explainable AI. Domain
          knowledge meets modern ML.
        - **S — System.** FastAPI services, dashboards, AI agents, and automation pipelines.
          Research outputs that other people can actually use.

        We collaborate across KIER (test & analysis, photovoltaics, energy storage,
        clean fuels, ICT, and more) and with external partners. Our bias is toward
        **methods that travel between domains** rather than one-off models for one dataset.
    design:
      columns: '1'

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
            <h4 class="text-xl font-semibold mb-1">Woonghee Lee, PhD</h4>
            <p class="text-sm opacity-75 mb-2">Senior Researcher</p>
            <p class="text-sm">
              Energy AI &amp; Computational Science Lab., KIER<br/>
              <a href="mailto:woongheelee&#64;kier&#46;re&#46;kr">Send email</a>
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
              Baekma Internship · Spring 2026<br/>
              <span class="opacity-75">Computer vision · XAI</span>
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
      title: 'Contact & Join Us'
      subtitle: ''
      text: |-
        We welcome inquiries from prospective graduate students (학연생) and
        undergraduate research interns.

        152 Gajeong-ro, Yuseong-gu, Daejeon 34129, South Korea

        Email: <a href="mailto:woongheelee&#64;kier&#46;re&#46;kr">Send email</a>
    design:
      columns: '1'
---
