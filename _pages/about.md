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

I am a PhD student in Electrical and Computer Engineering at **Michigan State University**, working with **[Dr. Xiaobo Tan](https://www.egr.msu.edu/~xbtan/)** in the **[Smart Microsystems Laboratory](https://smlab.msu.edu/)**. Before joining MSU, I received my **M.S. in Artificial Intelligence** and **B.S. in Automation** from **Tsinghua University**, where I was advised by **[Prof. Xiangyang Ji](https://www.au.tsinghua.edu.cn/info/1080/3178.htm)**. During my master's study, my research explored the intersection of **AI and healthcare**, including transfer learning with large models and multimodal data fusion for medical applications. I was also involved in research on **generative models**, particularly in text-to-motion generation.

My research focuses on **robot learning and perception for intelligent robotic systems**. I have worked on vision-based state perception for soft robots, enabling markerless shape reconstruction using visual observations. More recently, I have been exploring learning-based approaches such as imitation learning and world models for robot control and teleoperation.

---

# 🔥 News

- *2025.11* – Our paper **“AFT: Appearance-Based Feature Tracking for Markerless and Training-Free Shape Reconstruction of Soft Robots”** was accepted to **RA-L**.

- *2025.05* – Paper on **learning-based modeling of soft actuators using Euler spiral-inspired curvature** accepted to **MECC 2025**.

- *2024.09* – Our work **“ParCo: Part-Coordinating Text-to-Motion Synthesis”** was accepted to **ECCV 2024**.

- *2024.08* – Started my PhD in Electrical and Computer Engineering at Michigan State University, working with **Dr. Xiaobo Tan** in the Smart Microsystems Lab.

- *2024.03* – Paper on **coronary artery disease prediction using infrared thermography** published in **BMJ Health & Care Informatics**.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">RA-L 2025</div>
<a href="images/AFT_demo.mp4" target="_blank">
<video width="100%" autoplay loop muted playsinline>
  <source src="images/AFT_demo.mp4" type="video/mp4">
</video>
</a>
</div></div>
<div class='paper-box-text' markdown="1">

**AFT: Appearance-Based Feature Tracking for Markerless and Training-Free Shape Reconstruction of Soft Robots**

**Shangyuan Yuan**, Preston Fairchild, Yu Mei, Xinyu Zhou, Xiaobo Tan

- We propose a markerless vision-based method for reconstructing the shape of soft continuum robots using appearance-based feature tracking, enabling robust and training-free perception of soft robotic deformation.

[**Paper**]([#](https://arxiv.org/abs/2511.18215))

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">MECC 2025</div>
<a href="images/mecc_demo.jpg" target="_blank">
  <img src="images/mecc_demo.jpg" width="100%">
</a>
</div></div>
<div class='paper-box-text' markdown="1">

**Learning-Based Modeling of Soft Actuators Using Euler Spiral-Inspired Curvature**

Yu Mei, **Shangyuan Yuan**, Xinda Qi, Preston Fairchild, Xiaobo Tan

- A learning-based modeling framework for soft actuators using curvature representations inspired by Euler spirals to better capture deformation dynamics.

[**Paper**]([#](https://arxiv.org/abs/2504.18692))

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">ECCV 2024</div>
<a href="images/parco_demo.mp4" target="_blank">
<video width="100%" autoplay loop muted playsinline>
  <source src="images/parco_demo.mp4" type="video/mp4">
</video>
</a>
</div></div>
<div class='paper-box-text' markdown="1">

**ParCo: Part-Coordinating Text-to-Motion Synthesis**

Qiran Zou\*, **Shangyuan Yuan**\*, Shian Du, Yu Wang, Chang Liu, Yi Xu, Jie Chen, Xiangyang Ji
(\* Equal contribution)

- A generative framework for text-to-motion synthesis that models coordination between body parts to improve motion realism and controllability.

[**Paper**]([#](https://arxiv.org/abs/2403.18512)) [**Code**]([#](https://github.com/qrzou/ParCo))

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">BMJ 2024</div>
<a href="images/ir_demo.png" target="_blank">
  <img src="images/ir_demo.png" width="100%">
</a>
</div></div>
<div class='paper-box-text' markdown="1">

**Prediction of Coronary Artery Disease Based on Facial Temperature Information Captured by Non-contact Infrared Thermography**

Minghui Kung, Juntong Zeng, Shen Lin, Xuexin Yu, Chang Liu, Mengnan Shi, Runchen Sun, **Shangyuan Yuan**, Xiaocong Lian, Xiaoting Su, Yan Zhao, Zhe Zheng, Xiangyang Ji

- Predicting coronary artery disease using facial thermal patterns captured through non-contact infrared thermography.

[**Paper**]([#](https://pmc.ncbi.nlm.nih.gov/articles/PMC11149132/))

</div>
</div>

# 📖 Educations
- *2024.09 - now*, **Ph.D student, in Electrical and Computer Engineering**, Michigan State University. 
- *2021.09 - 2024.06*, **M.S. in Artificial Intelligence**, Tsinghua University.
- *2017.09 - 2021.06*, **B.S. in Automation**, Tsinghua University.

# 📫 Contact
Email: yuanshan@msu.edu  
GitHub: https://github.com/Dicomsky  
