---
title: "Semi-supervised Prostate Multi-Regional Semantic Segmentation with Patch-Based Plug-and-Play Correction Guidance"
collection: publications
category: manuscripts
permalink: /publication/2026-01-01-prostate-plug-and-play-correction
excerpt: 'A labeled patch guidance (LPG) plug-and-play module that optimizes pseudo-label quality for unlabeled data by dynamically mining anatomical priors from labeled data. Validated on PROMISE12, MSD, HPH55 and ACDC datasets.'
date: 2026-01-01
venue: 'IEEE Journal of Biomedical and Health Informatics (CAS Top Journal)'
paperurl: 'https://doi.org/10.1109/JBHI.2026.3732085'
citation: '<b>Z. Zhang</b>, Y. Zhang, Z. Zhou, J. Chen, U. A. Bhatti, W. Feng, M. Huang, and Z. Bai. (2026). &quot;Semi-supervised Prostate Multi-Regional Semantic Segmentation with Patch-Based Plug-and-Play Correction Guidance.&quot; <i>IEEE Journal of Biomedical and Health Informatics</i>, pp. 1-13. doi: 10.1109/JBHI.2026.3732085.'
---

The high cost of medical image annotation severely restricts the clinical application of precise prostate multi-regional segmentation. To address the bottlenecks of semi-supervised learning methods — insufficient alignment of local anatomical structures and pseudo-label noise accumulation — we propose **labeled patch guidance (LPG)**, a patch-level interactive enhancement module that optimizes pseudo-label quality for unlabeled data by dynamically mining anatomical prior knowledge from labeled data:

1. **Labeled Patch Mutual Correction (LPMC)**: performs bidirectional exchange of annotated data across augmented states, obtaining newly labeled data with enhanced model robustness and establishing a high-confidence anatomical prior patch pool for prostate regions.
2. **Unlabeled Patch Capture Learning (UPCL)**: injects reliable anatomical information into low-confidence patches of unlabeled data through feature-similarity retrieval from the high-confidence anatomical prior patch pool, improving the model's ability to recognize feature distributions in unlabeled data.

Comparative experiments demonstrate that LPG significantly enhances the performance of mainstream semi-supervised medical image segmentation models on **PROMISE12, MSD, HPH55, and ACDC** datasets. GradCAM-based interpretability analysis visually shows that the LPG-equipped model suppresses ambiguous boundaries in prostate segmentation and concentrates attention on regions of interest.

[Paper (IEEE Xplore)](https://doi.org/10.1109/JBHI.2026.3732085) | [Code (GitHub)](https://github.com/hai-medicallab/LPG)
