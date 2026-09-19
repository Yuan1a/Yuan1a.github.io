---
title: "Multi-Perturbation Consistency Learning for Semi-Supervised Medical Image Segmentation"
collection: publications
category: manuscripts
permalink: /publication/2025-12-11-multi-perturbation-consistency
excerpt: 'A cross-teaching semi-supervised framework integrating sparsely annotated 3D and 2D networks with multi-perturbation consistency learning and uncertainty-aware correction. Validated on ProstateX, HPH55, ACDC and LA datasets.'
date: 2025-12-11
venue: 'IEEE Journal of Biomedical and Health Informatics (CAS Top Journal)'
paperurl: 'https://doi.org/10.1109/JBHI.2025.3625190'
citation: '<b>Z. Zhang</b>, Y. Zhang, J. Chen, W. Feng, Z. Zhou, J. Zou, U. A. Bhatti, G. Wang, M. Huang, and Z. Bai. (2025). &quot;Multi-Perturbation Consistency Learning for Semi-Supervised Medical Image Segmentation.&quot; <i>IEEE Journal of Biomedical and Health Informatics</i>. doi: 10.1109/JBHI.2025.3625190.'
---

Existing semi-supervised learning (SSL) methods primarily rely on consistency learning, but most approaches only validate consistency under single perturbations — introducing multiple perturbations may cause consistency learning to fail and degrade performance. To address this, we propose a semi-supervised medical image segmentation method based on multi-perturbation consistency learning:

* A **cross-teaching framework** integrating sparsely annotated 3D and 2D networks, introducing network perturbations through multidimensional architectures, combined with strong/weak data augmentation for input perturbations.
* Two complementary **uncertainty-aware correction algorithms** targeting labeled and unlabeled data, overcoming the instability problem of multi-perturbation consistency learning.

Experiments on four datasets (ProstateX, HPH55, ACDC, and LA) demonstrate that the proposed method outperforms existing approaches and exhibits strong generalization with limited annotated data.

[Paper (IEEE Xplore)](https://doi.org/10.1109/JBHI.2025.3625190) | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41379896)
