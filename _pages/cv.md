---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.E. in Communication Engineering**, Hainan University (Double First-Class / 211), 2023.09 – 2026.06 (expected)
  * School of Information and Communication Engineering, GPA: 3.7/4.0
* **B.E. in Communication Engineering**, Chengdu University, 2018.09 – 2022.06
  * School of Electronic Information and Electrical Engineering, GPA: 3.39/4.0

Research Experience
======
* **Medical Image Segmentation with Limited Annotations** — National Natural Science Foundation of China (NSFC) Project, 2023.09 – 2025.05
  * Studied weakly/semi-supervised medical image segmentation for prostate MRI to reduce reliance on large-scale fine-grained annotations.
  * Proposed a weakly supervised segmentation method based on seed clusters (advanced prompt points) and geodesic distance transform.
  * Designed a multi-perturbation, multi-dimensional consistency learning strategy for semi-supervised segmentation.
  * Developed a labeled-data-guided, plug-and-play correction plugin embeddable into existing semi-supervised networks.
  * Tech stack: Python, PyTorch, OpenCV, NumPy, Matplotlib.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Patents & Intellectual Property
======
* Invention patent (under substantive examination): "Weakly supervised medical image segmentation method and system based on seed cluster generation", CN202410871110.9.
* Invention patent (under substantive examination): "Prostate sub-regional medical image segmentation method based on multi-perturbation consistency learning", CN202510138810.1.
* 6 software copyrights; 3 invention/utility-model patents in total.

Skills
======
* Programming: Python, PyTorch, OpenCV, NumPy, Matplotlib
* Research: medical image segmentation, weakly/semi-supervised learning, prompt-based learning
* Medical AI: RAG knowledge bases, local deployment of LLMs, embedding model fine-tuning
* Languages: Mandarin (native), English (CET-4 / CET-6)

Honors & Awards
======
* Second-Class Scholarship for Postgraduates, Hainan University (×3)
* Second-Class Scholarship (×2) and Third-Class Scholarship, Chengdu University
* Merit Student; Advanced Individual of Youth Volunteer; Outstanding League Member
