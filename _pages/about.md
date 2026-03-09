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

I am a PhD student in Electrical and Computer Engineering at **Michigan State University**, working with **[Dr. Xiaobo Tan](https://www.egr.msu.edu/~xbtan/)** in the **[Smart Microsystems Laboratory](https://smlab.msu.edu/)**. 

Before joining MSU, I received my **M.S. in Artificial Intelligence** and **B.S. in Automation** from **Tsinghua University**, where I was advised by **[Dr. Xiangyang Ji](https://www.au.tsinghua.edu.cn/info/1080/3178.htm)**. During my master's study, my research focused on **AI for healthcare**, including transfer learning with large models and multimodal data fusion. I also worked on **generative models**, particularly for text-to-motion generation.

### 🧠 Research Interests

My research aims to enable robots to understand and interact with the physical world through learning-based approaches. My previous work includes **vision-based perception for soft robots**, where I developed markerless methods for reconstructing the shape of soft continuum robots. I have also worked on **generative models for human motion synthesis**, focusing on coordinated text-to-motion generation. Currently, my research focuses on **robot learning**, particularly **imitation learning** and **world models for reinforcement learning**. I am currently working on several projects in these areas, with papers in preparation for submission.

### 🔬 Research Skills

- **Machine Learning**
  - World Models for Reinforcement Learning
  - Self-Supervised Learning (Contrastive Learning)
  - Transfer Learning (Parameter-Efficient Fine-Tuning)

- **Generative Models**
  - Motion Generation (VQ-VAE)
  - Action Generation (VAE, Diffusion Policy)

- **Robotics**
  - Teleoperation
  - Imitation Learning
  - Simulation (PyBullet)

- **Programming**
  - Python, C++, C#, Matlab
  - Deep learning algorithm development
  - Embedded systems (STM32 microcontrollers), Analog–digital circuit systems

---

# 📖 Educations
- *2024.09 - now*, **Ph.D student, in Robotics**, Michigan State University. 
- *2021.09 - 2024.06*, **M.S. in Artificial Intelligence**, Tsinghua University.
- *2017.09 - 2021.06*, **B.S. in Automation**, Tsinghua University.

# 🔥 News

- *2025.11* – Our paper **“AFT: Appearance-Based Feature Tracking for Markerless and Training-Free Shape Reconstruction of Soft Robots”** was accepted to **IEEE Robotics and Automation Letters (RA-L)**.

- *2025.05* – Our paper **“Learning-Based Modeling of Soft Actuators Using Euler Spiral-Inspired Curvature”** was accepted to **MECC 2025**.

- *2024.05* – Our paper **“ParCo: Part-Coordinating Text-to-Motion Synthesis”** was accepted to **ECCV 2024**.

- *2024.08* – Started my **PhD in Electrical and Computer Engineering at Michigan State University**, working with **Dr. Xiaobo Tan** in the **Smart Microsystems Lab**.

- *2024.03* – Our paper on **coronary artery disease prediction using infrared thermography** was published in **BMJ Health & Care Informatics**.

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

[**Paper**](https://arxiv.org/abs/2511.18215)

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

[**Paper**](https://arxiv.org/abs/2504.18692)

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

[**Paper**](https://arxiv.org/abs/2403.18512) [**Code**](https://github.com/qrzou/ParCo)

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

[**Paper**](https://pmc.ncbi.nlm.nih.gov/articles/PMC11149132/)

</div>
</div>


# 📝 Projects

<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">Ongoing Research</div>
<a href="images/wm_demo.png" target="_blank">
  <img src="images/wm_demo.png" width="100%">
</a>
</div>
</div>

<div class='paper-box-text' markdown="1">

**World Models for Atari Games**

- Training a world model from scratch to learn Atari game dynamics and enable reinforcement learning through imagination.
- Proposed a reference-conditioned observation generation mechanism that reduces pixel-level memorization and improves dynamics learning.
- Work in progress; a research paper based on this project is currently in preparation.

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">Ongoing Project</div>
<a href="images/teleop_demo.mp4" target="_blank">
<video width="100%" autoplay loop muted playsinline>
  <source src="images/teleop_demo.mp4" type="video/mp4">
</video>
</a>
</div>
</div>

<div class='paper-box-text' markdown="1">

**Learning Intuitive Teleoperation for Heterogeneous Leader–Follower Robot Systems**

- Developing a teleoperation system where a rigid robotic arm controls a soft continuum robot.
- Proposed a self-supervised method to automatically align the action spaces between heterogeneous robots.
- The approach is validated in simulation, with real-world experiments on the physical robot system currently in progress.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">Project</div>
<a href="images/CAD_pipeline.png" target="_blank">
  <img src="images/CAD_pipeline.png" width="100%">
</a>
</div></div>
<div class='paper-box-text' markdown="1">

**Facial Representation-Based Coronary Artery Disease (CAD) Diagnosis**

- Built a multi-camera acquisition array for large-scale facial data collection for medical analysis.
- Implemented multi-view 3D face reconstruction to recover facial geometric structures for physiological feature modeling.
- Applied transfer learning with parameter-efficient fine-tuning (PEFT) to adapt pretrained vision models to medical datasets.
- Developed a multimodal learning framework integrating facial imagery and clinical metadata for CAD prediction.

</div>
</div>


# 📫 Contact
Email: yuanshan@msu.edu
