---
title: "GraphWave Distillation for Continual Molecular Property Prediction"
venue: "NeurIPS 2025"
date: 2025-11-05
citation: "Scott, J., and Ibrahim, S. GraphWave Distillation for Continual Molecular Property Prediction. In Proceedings of NeurIPS, 2025."
codeurl: "https://github.com/synapse-lab-mirror/graphwave-distill"
paperurl: "/files/graphwave.pdf"
excerpt: "A spectral distillation objective that prevents catastrophic forgetting when a molecular property model is updated on new assays."
permalink: /publications/graphwave/
---

Molecular property predictors are frequently retrained as new assay data
arrives, and naive fine-tuning erases previously learned chemistry. We
formulate continual molecular learning as spectral distillation on graph
wavelet coefficients. The objective aligns the low-frequency and high-frequency
subspaces separately, which preserves scaffold-level knowledge while allowing
the model to adapt to new property labels. On a stream of twelve assays,
GraphWave retains 96.4% of the average performance of a jointly trained
oracle.
