---
title: 'Comparing SHAP and CRAFT Across Architectures for PEMFC SEM Images'
authors:
  - hyoeun
  - Woonjae Ruh
  - Yun Sik Kang
  - Byeongseon An
  - Woonghee Lee
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

> 🏆 **Bronze Award, Undergraduate / High-School Paper Competition** — ASK 2026 (Annual Symposium of the Korea Information Processing Society)

## Background

AI-driven materials development is increasingly active in renewable-energy
research. The PEMFC uses a platinum (Pt) catalyst to generate electricity from
hydrogen and oxygen and is a core module of hydrogen fuel-cell vehicles. The
catalyst layer degrades over long-term operation, leading to performance loss.
Accurate diagnosis of degradation is therefore essential for life-time
prediction.

While deep classifiers can distinguish degradation states from SEM images at
high accuracy, their decision processes are opaque to domain experts. XAI
methods address this, but most prior work studies a single model — leaving open
whether explanations transfer across architectures.

## Research Questions

1. **Are SHAP attributions consistent across model architectures?**
2. **Do the concepts extracted by CRAFT vary with model architecture?**

## Dataset and Classifiers

- 22 pristine (0 cycles) and 50 degraded (200K cycles) catalyst SEM images
  (50K magnification, 2 kV, SE) — 72 images total.
- 80/20 train–test split with ImageNet-pretrained initialization.
- All eight CNN/Transformer architectures reached 100% accuracy on the test
  set (5 pristine + 10 degraded images).
- For the XAI comparison we selected three architecturally distinct models:
  **GoogLeNet** (Inception), **DenseNet121** (dense connections), and
  **MaxViT-T** (multi-axis Vision Transformer).
- Random seed fixed at 42.
- Without pretraining, MaxViT-T reached only 80% accuracy, confirming that
  transfer learning is essential for this small-data regime.

Because all models reach the same accuracy, model selection cannot rely on
performance — making XAI-explanation dependence on architecture the central
question.

## Expert Reference

Following identical-location SEM (IL-SEM) studies [Shokhen 2022; Strandberg
2024], we used reported degradation indicators as the expert reference:
pristine samples show homogeneous flat surfaces; degraded samples exhibit Pt
agglomeration, carbon shrinkage, cracks, and dark regions.

Pt-agglomerate quantification confirmed statistically significant morphological
change: per-image agglomerate count increased 60% (131 ± 15 → 209 ± 24) and
median individual area decreased 14% (78 → 67 px) — Pt redistributes into more
numerous, smaller agglomerates with degradation.

## SHAP Meta-Analysis

We computed pixel-level Shapley values with a Gaussian-blur masker (σ = 128)
and aggregated across 26 settings of seven segmentation algorithms.

- Cross-architecture consensus is sparse: 2.7% at 0K, 0.8% at 200K.
- Inter-model IoU of 0.1–0.2 — **important regions differ by architecture even
  in attribution-based explanation**.
- However, at 200K **34% of the Pt-agglomerate region overlaps with
  cross-model consensus**, demonstrating that combining attribution with domain
  knowledge recovers physically meaningful structure.

## CRAFT Analysis

We ran CRAFT for the three models × four patch sizes (16, 32, 48, 64 px).
Mapping pixel scale (3.97 nm/px from the scale bar, 14.2 nm/px after resize to
224×224), the patches correspond to physical receptive fields of ≈ 227 / 454 /
680 / 907 nm.

- At 16 px, GoogLeNet extracted dark fine-structure concepts (mean intensity
  37) consistent with carbon-support corrosion.
- MaxViT-T's dominant concept had intensity 118 and DenseNet121's had 81 —
  **all three models attended to darker regions than 0K (136–163)**, a shared
  trend.
- As the patch grew, the contrast between 0K and 200K shrank; at 48–64 px
  reversals occurred — **CRAFT analysis combined with domain knowledge requires
  patches small enough to capture fine structure**.

## Conclusion

Both methods exhibit architecture-dependent explanations, yet they agree on
trends consistent with established degradation indicators: SHAP's cross-model
consensus concentrates around Pt agglomerates, and CRAFT picks up brighter
surfaces at 0K and darker degradation structures at 200K.

Two takeaways: equally accurate models can still produce different XAI
explanations, so interpretation should rely on **multi-method, multi-model
comparison combined with domain knowledge**.

Future work extends the binary 0K vs. 200K classification to multi-class
(50K, 100K, 150K, 200K) to track how a model's reasoning shifts with
degradation progress.

## Acknowledgement

This work was supported by the basic R&D project of the Korea Institute of
Energy Research (C6-2402-08).
