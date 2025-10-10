---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a second-year Master's student of Computer Science and Technology at Sun Yat-sen University, under the supervision of [Prof. Xianwei Zhang](https://xianweiz.github.io/). Previously I completed my Bachelor's degree at South China University of Technology (SCUT).

I am particularly interested in building practical, scalable and efficient systems for machine learning (MLSys) like serving system. Currently, my research focuses on optimizing KV Cache management, developing efficient inference scheduling strategies, and improving RLVR efficiency through advanced sampling techniques. 

I warmly welcome any academic discussions and collaborations! If you are interested in my research work or have suitable internship opportunities, please feel free to contact me through:
- Email: xuhx56@mail2.sysu.edu.cn
- WeChat ID: hx1737006628
- [**My Resume(中文简历)**](./resume.pdf)

# 🛠️ Skills 
- Programming Languages: Python, C++, Shell
- Frameworks: PyTorch, VLLM, SGLang, slime
- Tools: Git, Linux, Docker, Nsight System




# 🔥 News
- *2025.09*: &nbsp;🎉🎉 My first paper [DynaPipe](https://neurips.cc/virtual/2025/poster/119240) has been accepted by NeurIPS 2025. 
- *2025.08*: &nbsp;Joined **SenseTime** as a research intern, focusing on **efficient reinforcement learning for LLM**.  

# 📝 Publications

<button type="button" class="btn btn-sm btn-primary" disabled 
  style="opacity: 1; font-size: 13px; padding: 2.5px 7px; line-height: 1;">
  NeurIPS'25
</button> **[DynaPipe: Dynamic Layer Redistribution for Efficient Serving of LLMs with Pipeline Parallelism](https://neurips.cc/virtual/2025/poster/119240)** <br>
**Hongxin Xu**<sup>#</sup>, Tianyu Guo<sup>#</sup>, Xianwei Zhang<br>

<button type="button" class="btn btn-sm btn-primary" disabled 
  style="opacity: 1; font-size: 13px; padding: 2.5px 7px; line-height: 1;">
  arXiv
</button> **[Bullet: Boosting GPU Utilization for LLM Serving via Dynamic Spatial-Temporal Orchestration](https://arxiv.org/abs/2504.19516)** <br>
Zejia Lin, **Hongxin Xu**, Guanyi Chen, Zhiguang Chen, Yutong Lu, and Xianwei Zhang. <br>

<sup>#</sup>Equal contribution<br>


# 💻 Internships
- *2025.08 – Present*: **RL Infrastructure Research Intern**, SenseTime, Shenzhen.  
Supervised by [Shihao Bai](https://scholar.google.com.hk/citations?hl=ja&user=k3orJesAAAAJ&view_op=list_works&sortby=pubdate) and [Ruihao Gong](https://xhplus.github.io/).
- *2023.06 - 2023.08*, **Algorithm Engineer Intern**, Research and Development Center, China Guangfa Bank, Foshan


<!-- # 🚀 Projects 
- *2025.01 - now* **YatCC-AI**
  - Successfully deployed the DeepSeek-R1 model on a supercomputing platform, ensuring immediate accessibility for student instructional use.
  - Built a Prometheus + Grafana monitoring system to provide real-time visualization of model runtime status and resource utilization.
  - Developed a RAGFlow-based retrieval-augmented generation system, enabling students to efficiently search and access documentation for compiler course lab assignments.

<!-- - *2024.06 - 2024.08* **Large Language Model Inference Framework**
  - Built a high-performance inference framework from scratch supporting LLaMA/Qwen models
  - Developed efficient CUDA operators including RMSNorm, GEMV, and multi-head attention
  - Implemented KV Cache mechanism for optimized inference with dynamic batching support
  - Designed unified memory management system for automatic CPU/GPU memory handling
  - Utilized Nsight Compute for performance analysis and operator optimization -->

<!-- - *2022.11 - 2023.02* **Single-Machine SQL Database (CMU-15445)**
  - Implemented a thread-safe buffer pool with LRU-K replacement algorithm
  - Developed concurrent B+ Tree index with optimistic locking
  - Built query execution engine supporting SELECT, JOIN, and other SQL operations

- *2022.09 - 2022.12* **RISC-V Unix-like Operating System (MIT6.S081)**
  - Implemented virtual memory management with lazy allocation
  - Developed copy-on-write fork and alarm system calls
  <!-- - Enhanced file system performance with multi-threaded block cache -->


# 🎖 Honors and Awards
- *2025,09* First-Class Scholarship, Sun Yat-sen University
- *2024.09* Second-Class Scholarship, Sun Yat-sen University
- *2023.09 & 2022.09* Second-Class Scholarship, South China University of Technology
- *2021.09* Anjubao Enterprise Scholarship (Ranked 5/73)

# 📖 Educations
- *2024.09 - present*, Master, School of Computer Science, Sun Yat-sen University
- *2020.09 - 2024.06*, Undergraduate, School of Computer Science and Engineering, South China University of Technology(12/166)
