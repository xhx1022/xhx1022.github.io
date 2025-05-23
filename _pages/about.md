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

I am a first-year Master's student at the School of Computer Science, Sun Yat-sen University, under the supervision of [Prof. Xianwei Zhang](https://xianweiz.github.io/). Previously I completed my Bachelor's degree at the School of Computer Science and Engineering, South China University of Technology (SCUT).

I am particularly interested in building practical, scalable and efficient systems for machine learning (MLSys) like serving system. Currently, my research focuses on optimizing KV Cache management, developing efficient inference scheduling strategies, and designing multi-agent systems. 

I warmly welcome any academic discussions and collaborations! If you are interested in my research work or have suitable internship opportunities, please feel free to contact me through:
- Email: xuhx56@mail2.sysu.edu.cn
- WeChat ID: hx1737006628
- [My Resume(中文简历)](./resume.pdf)

# 🛠️ Skills 
- Programming Languages: Python, C++, Shell
- Frameworks: PyTorch, VLLM, SGLang
- Tools: Git, Linux, Docker




<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📝 Publications  -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->


# 🚀 Projects 
- *2025.01 - now* **YatCC-AI**
  - Deployed Deepseek-R1 model for course students' use
  - Responsible for the model serving system development and maintenance

- *2024.06 - 2024.08* **Large Language Model Inference Framework**
  - Built a high-performance inference framework from scratch supporting LLaMA/Qwen models
  - Developed efficient CUDA operators including RMSNorm, GEMV, and multi-head attention
  - Implemented KV Cache mechanism for optimized inference with dynamic batching support
  - Designed unified memory management system for automatic CPU/GPU memory handling
  - Utilized Nsight Compute for performance analysis and operator optimization

- *2022.11 - 2023.02* **Single-Machine SQL Database (CMU-15445)**
  - Implemented a thread-safe buffer pool with LRU-K replacement algorithm
  - Developed concurrent B+ Tree index with optimistic locking
  - Built query execution engine supporting SELECT, JOIN, and other SQL operations

- *2022.09 - 2022.12* **RISC-V Unix-like Operating System (MIT6.S081)**
  - Implemented virtual memory management with lazy allocation
  - Developed copy-on-write fork and alarm system calls
  - Enhanced file system performance with multi-threaded block cache


# 🎖 Honors and Awards
- *2024.09* Second-Class Scholarship, Sun Yat-sen University
- *2023.09 & 2022.09* Second-Class Scholarship, South China University of Technology
- *2021.09* Anjubao Enterprise Scholarship (Ranked 5/73)

# 📖 Educations
- *2024.09 - present*, Master, School of Computer Science, Sun Yat-sen University
- *2020.09 - 2024.06*, Undergraduate, School of Computer Science and Engineering, South China University of Technology(12/166)


# 💻 Internships
- *2023.06 - 2023.08*, Algorithm Engineer Intern, Research and Development Center, China Guangfa Bank, Foshan
