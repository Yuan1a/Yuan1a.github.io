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
* **M.E. in Communication Engineering**, Hainan University (Double First-Class / 211), Haikou, 2023.09 – 2026.06
  * School of Information and Communication Engineering, GPA: 3.7/4.0
* **B.E. in Communication Engineering**, Chengdu University, Chengdu, 2018.09 – 2022.06
  * School of Electronic Information and Electrical Engineering, GPA: 3.39/4.0

Work Experience
======
* **Group Management Trainee**, Shanghai Huali Microelectronics Corporation (Hua Hong Group), Shanghai, 2026.07 – present
  * Shanghai Huali is a subsidiary of Hua Hong Group, a state-owned IC manufacturing group. It operates two 12-inch fully automated wafer fabs (Fab 5 & Fab 6) in Zhangjiang Science City, with mass-production technology covering 65/55nm to 28nm (logic, RF, high-voltage, embedded flash, ultra-low-power, NOR flash and CIS specialty platforms).

* **AI Application Engineer (Intern)**, Hainan Xingjie'an Technology Group, Hainan, 2025.03 – 2025.05
  * Backend development and maintenance of a blockchain-based intelligent medical platform integrating medical imaging analysis with LLMs; delivered an integrated AI-assisted pipeline from image screening to report generation via an AI imaging engine, RAG and Tool-Calling.
  * Built CT/MRI medical imaging task models with **PyTorch** and deployed high-performance inference APIs with **FastAPI** for automatic lesion screening.
  * Local LLM deployment with **Xinference**; invocation abstraction via **Spring AI**; session memory with **Redis**.
  * Built a private **RAG** knowledge base: fine-tuned the **BGE-large-zh** embedding model on public medical QA datasets; extracted medical knowledge with **YOLO + OCR**; built the vector knowledge base with **Milvus**; enhanced LLM medical-domain capability via RAG + prompt optimization.

* **R&D Engineer**, Chengdu Zhiwei Optical Measurement Technology Co., Ltd., Chengdu, 2022.05 – 2023.06
  * Hardware selection, hardware system design and inspection algorithm development for chip packaging/testing fabs and defense industry customers.
  * **WB pad defect inspection system**:
    * Designed a non-invasive image acquisition hardware system (high-resolution industrial camera + telecentric lens + photoelectric trigger) with high-precision motion control, solving the closed-interface problem of imported equipment and enabling non-contact, high-quality chip image acquisition.
    * Developed multi-class chip defect detection pipelines based on traditional image processing, meeting production-line real-time requirements with >95% defect detection accuracy.
  * **Micro-deformation measurement system (pre-research)**:
    * Built a high-precision acquisition platform: 20MP binocular industrial cameras + customized matrix speckle laser (100mm optical baseline), capturing ambient-light-resistant laser speckle images.
    * Implemented speckle extraction with OpenCV; eliminated speckle connectivity issues via bilinear interpolation; solved multi-point three-axis coordinates with the similar-triangle method; realized planar 3D reconstruction with pseudo-color maps.
    * System validation: 0.02mm accuracy in X/Y directions; Z-direction accuracy better than 0.01mm on 80% of measured points.

Research Experience
======
* **Medical Image Segmentation with Limited Annotations** — National Natural Science Foundation of China (NSFC) Project, 2023.09 – 2025.05
  * Studied weakly/semi-supervised medical image segmentation for prostate MRI to reduce reliance on large-scale fine-grained annotations.
  * Proposed a weakly supervised segmentation method based on seed clusters (advanced prompt points) and geodesic distance transform.
  * Designed a multi-perturbation, multi-dimensional consistency learning strategy for semi-supervised segmentation.
  * Developed a labeled-data-guided, plug-and-play correction plugin embeddable into existing semi-supervised networks.
  * Tech stack: Python, PyTorch, OpenCV, NumPy, Matplotlib.

Project Experience
======
* **WanderAI — Travel Assistant**, 2025.05 – 2025.07
  * An autonomous travel-planning AI agent based on the ReAct paradigm: parses complex travel requirements, autonomously invokes tool chains (maps, web search, PDF generation), and outputs executable structured travel plans.
  * Unified LLM integration via **Spring AI** (Qwen, Ollama); prompt engineering with role definition and few-shot prompting, validated on Alibaba Cloud Bailian.
  * Re-Reading Advisor (CallAroundAdvisor) for complex queries; tool annotations for file operations, web search/scraping, terminal operations, resource download and PDF generation.
  * ReAct agent with task decomposition, autonomous decision-making and tool selection; agent-loop safeguards (max-step limit, state management, infinite-loop detection).
  * Integrated Amap (Gaode) **MCP** via Spring AI MCP Client (stdio) for location-based recommendations.
  * Tech stack: Spring Boot 3, Spring AI, Tool Calling, MCP.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Patents & Intellectual Property
======
* Invention patent (**granted**): "Prostate sub-regional medical image segmentation method based on multi-perturbation consistency learning", CN202510138810.1.
* Invention patent (under substantive examination): "Weakly supervised medical image segmentation method and system based on seed cluster generation", CN202410871110.9.
* Utility-model patent (granted, 2023): "A triggering device and system for chip defect detection", CN202223185270.3.
* 6 software copyrights.

Skills
======
* **Programming**: Java, Python, C++; solid grasp of data structures (stacks, queues, binary trees) and good coding practices.
* **Computer Vision**: traditional image processing for industrial defect detection and high-precision measurement; end-to-end AI model building, training and deployment.
* **LLM Application Development**: RAG, Tool-Calling, ReAct agents; complete LLM application project experience.
* **Database & Middleware**: MySQL (transactions, indexing, locking, SQL optimization); Redis (data types, caching, persistence, distributed locks, HA clusters); Kafka (message loss/duplication, ordered consumption, backlog handling).
* **Testing & Debugging**: Postman, Apifox, JMeter; GDB debugging on Linux.
* **Others**: Linux, MATLAB, industrial camera SDKs, MFC visualization framework.
* **Languages**: Mandarin (native), English (CET-4 / CET-6).

Honors & Awards
======
* Second-Class Scholarship for Postgraduates, Hainan University (×3)
* Second-Class Scholarship (×2) and Third-Class Scholarship, Chengdu University
* Merit Student; Advanced Individual of Youth Volunteer; Outstanding League Member
