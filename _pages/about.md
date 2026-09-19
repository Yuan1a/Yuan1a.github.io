---
permalink: /
title: "Zhiyuan Zhang (章志远)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Master's student (expected to graduate in June 2026) at the School of Information and Communication Engineering, **Hainan University**, China. My research focuses on **medical image segmentation**, especially weakly supervised and semi-supervised deep learning for 3D prostate MRI segmentation. I am also interested in **LLM/RAG-based medical AI applications**.

I have participated in a **National Natural Science Foundation of China (NSFC)** project on medical image segmentation with limited annotations, and have published papers in **CAS Top journals** (IEEE Journal of Biomedical and Health Informatics) together with invention patent applications.

📧 Feel free to reach me at: **zzy_1230@outlook.com**

Research Interests
======
1. **Medical Computer Vision**: medical image segmentation, 3D prostate MRI segmentation, weakly/semi-supervised deep learning, prompt-based medical image learning.
1. **LLM + Medical AI**: RAG knowledge base construction, local deployment of medical LLMs, fine-tuning of medical knowledge embedding models.
1. **Industrial Vision Measurement** (engineering-oriented): binocular vision, laser speckle 3D reconstruction, industrial defect detection.

Education
======
* **M.E. in Communication Engineering** (2023.09 – 2026.06), Hainan University (Double First-Class / 211), School of Information and Communication Engineering. GPA: 3.7/4.0
  * Research on medical image segmentation algorithms; participant in an NSFC project; first-author paper in a CAS Top journal; multiple invention patents.
* **B.E. in Communication Engineering** (2018.09 – 2022.06), Chengdu University, School of Electronic Information and Electrical Engineering. GPA: 3.39/4.0
  * Solid foundation in communications and image processing; multiple scholarships.

Research Project
======
**Medical Image Segmentation with Limited Annotations** — NSFC Project (2023.09 – 2025.05)

Medical image annotation is expensive. Targeting prostate MRI, this project studies **weakly supervised and semi-supervised segmentation algorithms** to reduce the reliance on large-scale fine-grained annotations while improving model accuracy and generalization.

*Tech stack: Python, PyTorch, OpenCV, NumPy, Matplotlib.*

Key contributions:

1. **Weakly supervised prostate segmentation via advanced prompt points**: a seed-cluster (advanced prompt points) + geodesic distance transform method that completes 3D prostate MRI segmentation with only a few prompt points.
1. **Semi-supervised segmentation via multi-dimensional feature collaboration**: a multi-perturbation, multi-dimensional consistency learning strategy that improves the generalization of semi-supervised models on medical images.
1. **Plug-and-play correction plugin guided by labeled data**: a general plug-in module that uses a few annotations to correct pseudo-labels of unlabeled samples; it can be embedded into existing semi-supervised segmentation networks to boost performance.

Selected Publications
======
1. **Z. Zhang**, Y. Zhang, J. Chen, et al. "Multi-Perturbation Consistency Learning for Semi-Supervised Medical Image Segmentation." *IEEE Journal of Biomedical and Health Informatics* (CAS Top), 2025.
1. J. Zou, M.-X. Huang, Y. Zhang, **Z.-Y. Zhang**, et al. "ACEA-Net: Weakly Supervised Prostate 3D MRI Image Segmentation via Advanced Prompt Points." *IEEE Journal of Biomedical and Health Informatics* (CAS Top), 2025.
1. "Semi-supervised Prostate Multi-Regional Semantic Segmentation with Patch-Based Plug-and-Play Correction Guidance." CAS Top journal, under review (first round).

See the full list on the [Publications](/publications/) page.

Patents
======
* Invention patent: "Weakly supervised medical image segmentation method and system based on seed cluster generation" (CN202410871110.9, under substantive examination).
* Invention patent: "Prostate sub-regional medical image segmentation method based on multi-perturbation consistency learning" (CN202510138810.1, under substantive examination).
* 6 software copyrights; 3 invention/utility-model patents in total.

Honors & Awards
======
* Second-Class Scholarship for Postgraduates, Hainan University (×3)
* Second-Class Scholarship (×2) and Third-Class Scholarship, Chengdu University
* Merit Student; Advanced Individual of Youth Volunteer; Outstanding League Member
* CET-4 / CET-6
