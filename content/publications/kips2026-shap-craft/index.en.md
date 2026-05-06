---
title: 'Comparing SHAP and CRAFT Across Architectures for PEMFC SEM Images'
authors:
  - hyoeun
  - Woonjae Ruh
  - Yun Sik Kang
  - Byeongseon An
  - woongheelee
author_notes:
  - 'First author'
  - ''
  - ''
  - ''
  - 'Corresponding author'
date: '2026-05-06'
publishDate: '2026-05-06'
publication_types:
  - paper-conference
publication: 'Annual Symposium of KIPS (ASK), 2026 · Undergraduate / High-School Paper Competition (Paper ID: KIPS_C2026A0116)'
publication_short: 'ASK 2026 · 🏆 Bronze Award (Undergraduate Track)'
featured: true

award: 'Bronze Award, Undergraduate / High-School Paper Competition'

abstract: |-
  We apply the attribution method SHAP and the concept-extraction method CRAFT
  to deep-learning models that classify PEMFC catalyst-layer degradation from SEM
  images, and analyze how XAI explanations depend on model architecture across
  three architecturally distinct backbones (GoogLeNet, DenseNet121, MaxViT-T).
  Both methods produce architecture-dependent explanations, but they share
  common trends consistent with degradation indicators: SHAP's cross-architecture
  consensus regions concentrate around platinum (Pt) agglomerates, and CRAFT
  captures bright homogeneous surfaces at 0 K and dark degraded structures at
  200 K cycles. The results suggest that interpreting XAI explanations of
  scientific images benefits from (i) combining domain knowledge with attribution
  outputs, (ii) selecting an appropriate analysis scale, and (iii) comparing
  multiple methods across multiple model families.

summary: |-
  Cross-architecture comparison of SHAP and CRAFT on PEMFC catalyst SEM images
  for degradation classification. Co-authored with KIER's analysis and hydrogen
  fuel cell teams.

tags:
  - Explainable AI
  - SHAP
  - CRAFT
  - PEMFC
  - SEM image classification
  - Hydrogen fuel cells

show_related: false
---
