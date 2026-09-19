---
permalink: /
title: "Zhiyuan Zhang (章志远)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I received my **M.E. in Communication Engineering** from **Hainan University** (Double First-Class / 211) in June 2026. I am currently a **Group Management Trainee at Shanghai Huali Microelectronics Corporation** (Hua Hong Group), a leading IC foundry in China.

My research focuses on **medical image segmentation**, especially weakly supervised and semi-supervised deep learning for 3D prostate MRI segmentation, and **LLM/RAG-based medical AI applications**. During my master's study, I participated in a **National Natural Science Foundation of China (NSFC)** project on medical image segmentation with limited annotations. I have published **3 SCI papers in CAS Top journals** (IEEE Journal of Biomedical and Health Informatics) and 1 Chinese journal paper, and hold multiple invention/utility-model patents and software copyrights.

📧 Feel free to reach me at: **zzy_1230@outlook.com**

Research Interests
======
1. **Medical Computer Vision**: medical image segmentation, 3D prostate MRI segmentation, weakly/semi-supervised deep learning, prompt-based medical image learning.
1. **LLM + Medical AI**: RAG knowledge base construction, local deployment of medical LLMs, fine-tuning of medical knowledge embedding models.
1. **Industrial Vision Measurement**: binocular vision, laser speckle 3D reconstruction, industrial defect detection.

Education
======
* **M.E. in Communication Engineering** (2023.09 – 2026.06), Hainan University (Double First-Class / 211), School of Information and Communication Engineering, Haikou. GPA: 3.7/4.0
  * Research on medical image segmentation algorithms; participant in an NSFC project; first-author paper in a CAS Top journal; multiple invention patents.
* **B.E. in Communication Engineering** (2018.09 – 2022.06), Chengdu University, School of Electronic Information and Electrical Engineering, Chengdu. GPA: 3.39/4.0
  * Solid foundation in communications and image processing; multiple scholarships.

Work Experience
======
* **Group Management Trainee** (2026.07 – present), Shanghai Huali Microelectronics Corporation (上海华力集成电路制造有限公司), Shanghai
  * Subsidiary of **Hua Hong Group**, a state-owned IC manufacturing group with advanced mainstream process technology. Founded in 2010, Shanghai Huali operates two 12-inch fully automated wafer fabs (Fab 5 & Fab 6) in Zhangjiang Science City, with mass-production technology covering 65/55nm to 28nm, including logic, RF, high-voltage, embedded flash, ultra-low-power, NOR flash and CIS specialty platforms.
* **AI Application Engineer (Intern)** (2025.03 – 2025.05), Hainan Xingjie'an Technology Group, Hainan
  * Backend development of a blockchain-based intelligent medical platform integrating medical imaging analysis with LLMs; built an integrated AI-assisted pipeline from image screening to report generation.
  * Built CT/MRI imaging models with PyTorch and deployed high-performance inference APIs with FastAPI for automatic lesion screening.
  * Deployed local LLMs via Xinference with Spring AI abstraction; implemented session memory with Redis.
  * Built a private RAG knowledge base: fine-tuned the BGE-large-zh embedding model on public medical QA datasets; extracted medical knowledge with YOLO + OCR; built the vector knowledge base with Milvus.
* **R&D Engineer** (2022.05 – 2023.06), Chengdu Zhiwei Optical Measurement Technology Co., Ltd., Chengdu
  * Hardware selection, system design and algorithm development for defect inspection targeting chip packaging/testing fabs and defense industry customers.
  * **WB pad defect inspection system**: designed a non-invasive image acquisition system (high-resolution industrial camera + telecentric lens + photoelectric trigger); developed multi-class chip defect detection pipelines with traditional image processing, achieving >95% accuracy with production-line real-time performance.
  * **Micro-deformation measurement system (pre-research)**: built a 20MP binocular camera + customized matrix speckle laser platform; implemented speckle extraction and three-axis displacement measurement with OpenCV; achieved 0.02mm X/Y accuracy and <0.01mm Z accuracy on 80% of measured points.

Research Project
======
**Medical Image Segmentation with Limited Annotations** — NSFC Project (2023.09 – 2025.05)

Medical image annotation is expensive. Targeting prostate MRI, this project studies **weakly supervised and semi-supervised segmentation algorithms** to reduce the reliance on large-scale fine-grained annotations while improving model accuracy and generalization.

*Tech stack: Python, PyTorch, OpenCV, NumPy, Matplotlib.*

Key contributions:

1. **Weakly supervised prostate segmentation via advanced prompt points**: a seed-cluster (advanced prompt points) + geodesic distance transform method that completes 3D prostate MRI segmentation with only a few prompt points.
1. **Semi-supervised segmentation via multi-dimensional feature collaboration**: a multi-perturbation, multi-dimensional consistency learning strategy that improves the generalization of semi-supervised models on medical images.
1. **Plug-and-play correction plugin guided by labeled data**: a general plug-in module that uses a few annotations to correct pseudo-labels of unlabeled samples; it can be embedded into existing semi-supervised segmentation networks to boost performance.

Selected Project
======
**WanderAI — Travel Assistant** (2025.05 – 2025.07)

An autonomous travel-planning AI agent based on the **ReAct** paradigm. It parses complex travel requirements, autonomously invokes tool chains (maps, web search, PDF generation), collects information, plans routes and budgets, and outputs an executable structured travel plan.

*Tech stack: Spring Boot 3, Spring AI, Tool Calling, MCP.*

* Unified LLM integration via Spring AI (Qwen, Ollama, etc.); prompt engineering with role definition and few-shot prompting, validated on Alibaba Cloud Bailian.
* Implemented a Re-Reading Advisor (CallAroundAdvisor) to improve complex query handling; tool annotations for file operations, web search/scraping, terminal operations and PDF generation.
* Agent loop safeguards: max-step limits, agent state management and infinite-loop detection; integrated Amap (Gaode) MCP via Spring AI MCP Client (stdio) for location-based POI recommendations.

Publications
======
1. **Z. Zhang**, Y. Zhang, J. Chen, et al. "Multi-Perturbation Consistency Learning for Semi-Supervised Medical Image Segmentation." *IEEE Journal of Biomedical and Health Informatics* (CAS Top), 2025.
1. J. Zou, M.-X. Huang, Y. Zhang, **Z.-Y. Zhang**, et al. "ACEA-Net: Weakly Supervised Prostate 3D MRI Image Segmentation via Advanced Prompt Points." *IEEE Journal of Biomedical and Health Informatics* (CAS Top), 2025.
1. **Z. Zhang**, Y. Zhang, Z. Zhou, et al. "Semi-supervised Prostate Multi-Regional Semantic Segmentation with Patch-Based Plug-and-Play Correction Guidance." *IEEE Journal of Biomedical and Health Informatics* (CAS Top), 2026.
1. 张建伟, 陈二阳, **章志远**, 等. "基于激光散斑的非接触式三维形变测量技术研究." *成都大学学报(自然科学版)*, 2023, 42(2): 162-167.

See the full list on the [Publications](/publications/) page.

Patents & Intellectual Property
======
* Invention patent (**granted**): "Prostate sub-regional medical image segmentation method based on multi-perturbation consistency learning", CN202510138810.1.
* Invention patent (under substantive examination): "Weakly supervised medical image segmentation method and system based on seed cluster generation", CN202410871110.9.
* Utility-model patent (granted, 2023): "A triggering device and system for chip defect detection", CN202223185270.3.
* 6 software copyrights.

Skills
======
* **Programming**: Java, Python, C++; solid data structures and coding practices.
* **Computer Vision**: traditional image processing for industrial defect detection and high-precision measurement; end-to-end AI model building, training and deployment.
* **LLM Application Development**: RAG, Tool-Calling, ReAct agents; full-cycle LLM application project experience.
* **Database & Middleware**: MySQL (transactions, indexing, locking, SQL optimization); Redis (caching, persistence, distributed locks, HA clusters); Kafka (message reliability, ordering, backlog handling).
* **Testing & Debugging**: Postman, Apifox, JMeter; GDB debugging on Linux.
* **Others**: Linux, MATLAB, industrial camera SDKs, MFC.

Honors & Awards
======
* Second-Class Scholarship for Postgraduates, Hainan University (×3)
* Second-Class Scholarship (×2) and Third-Class Scholarship, Chengdu University
* Merit Student; Advanced Individual of Youth Volunteer; Outstanding League Member
* CET-4 / CET-6
