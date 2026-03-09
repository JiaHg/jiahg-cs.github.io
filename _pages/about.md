---
permalink: /
title: "Jiafan Liu"
excerpt: "Jiafan Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
--- 

<style>
/* Fix Font Awesome icon loading on homepage by forcing absolute CDN path */
@font-face {
  font-family: 'FontAwesome';
  src: url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.woff2') format('woff2'),
       url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

.cv-btn {
  display: inline-block;
  margin: 12px 0 20px 0;
  padding: 8px 20px;
  background-color: #2c7be5;
  color: #fff !important;
  border-radius: 5px;
  font-weight: bold;
  font-size: 0.95em;
  text-decoration: none !important;
  transition: background-color 0.2s;
}
.cv-btn:hover {
  background-color: #1a5fbf;
}
.pub-block {
  display: flex;
  align-items: flex-start;
  gap: 16px;
  margin-bottom: 24px;
  padding-bottom: 20px;
  border-bottom: 1px solid #eee;
}
.pub-img {
  flex-shrink: 0;
  width: 160px;
  height: 120px;
  object-fit: contain;
  object-position: center;
  background-color: #fff;
  border: 1px solid #eee;
}
.pub-text {
  flex: 1;
  font-size: 0.9em;
  line-height: 1.6;
}
.edu-block {
  display: flex;
  align-items: flex-start;
  gap: 16px;
  margin-bottom: 24px;
  padding-bottom: 20px;
  border-bottom: 1px solid #eee;
}
.edu-img {
  flex-shrink: 0;
  width: 80px;
  height: 70px;
  object-fit: contain;
  object-position: center;
}
.edu-text {
  flex: 1;
  font-size: 0.9em;
  line-height: 1.6;
}
.section-title {
  font-size: 1.5em;
  font-weight: bold;
  margin-top: 1.5em;
  margin-bottom: 0.8em;
  border-bottom: 2px solid #ddd;
  padding-bottom: 4px;
}
.oral-badge {
  color: red;
  font-weight: bold;
}
.research-grid {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
  margin: 12px 0 20px 0;
}
.research-card {
  flex: 1;
  min-width: 180px;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 14px 16px;
  background: #f9f9f9;
}
.research-card h4 {
  margin: 0 0 6px 0;
  font-size: 0.95em;
  font-weight: bold;
  color: #2c7be5;
}
.research-card p {
  margin: 0;
  font-size: 0.82em;
  color: #444;
  line-height: 1.5;
}
</style>

Jiafan Liu received her Master's degree from [Nanyang Technological University, Singapore](https://www.ntu.edu.sg) in June 2025, advised by [Prof. Alex Kot](https://dr.ntu.edu.sg/entities/person/Kot-Chichung-Alex). She is fortunate to have internships and collaborations with [SIAT, CAS](https://www.siat.ac.cn/), supervised by [Prof. Ruxin Wang](https://people.ucas.edu.cn/~rxwang) and [Westlake University](https://www.westlake.edu.cn/), supervised by [Prof. Stan Z. Li](https://scholar.google.com/citations?user=Y-nyLGIAAAAJ&hl=zh-CN), [Dr. Cheng Tan](https://chengtan9907.github.io/). After a GAP half year, she decided to pursue her academic dream and she is actively looking for RA or PhD positions opening from now!

Her research broadly lies in computer vision and deep learning. Currently focused on Scalable Post-training methods for Large Language Models.

**Research Interests**

<div class="research-grid">
  <div class="research-card">
    <h4>🎯 SFT & RL</h4>
    <p>Supervised fine-tuning and reinforcement learning for aligning large language models, including reward modeling, RLHF, and preference optimization (DPO/PPO).</p>
  </div>
  <div class="research-card">
    <h4>🧠 Memory-Agent</h4>
    <p>Building long-context and memory-augmented agents capable of retrieving, updating, and reasoning over external knowledge across multi-turn interactions.</p>
  </div>
  <div class="research-card">
    <h4>⚡ Test-time Scaling</h4>
    <p>Improving model reasoning at inference time via chain-of-thought, self-consistency, best-of-N sampling, and process reward models without additional training.</p>
  </div>
</div>

<a class="cv-btn" href="/files/CV_JiafanLiu.pdf" download>📄 Download CV</a>

---

<div class="section-title">Publications</div>

<div class="pub-block">
  <img class="pub-img" src="../images/paper_fetac.png" alt="FETAC paper">
  <div class="pub-text">
    <strong>Feature Transformation and Statistical Calibration for Cross-Domain Few-Shot Classification.</strong><br>
    <strong>Jiafan Liu</strong>, Jin Deng, Jinrong Cui, Wei Luo<br>
    Engineering Applications of Artificial Intelligence (<strong>EAAI</strong>), 2025 &nbsp;<strong>(SCI Q1 Journal)</strong><br>
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0952197625011820?via%3Dihub">Paper</a> |
    <a href="https://github.com/JiaHg/fetac">Code</a>
  </div>
</div>

<div class="pub-block">
  <img class="pub-img" src="../images/paper_motion.png" alt="Motion paper">
  <div class="pub-text">
    <strong>A Comprehensive Body Part Adaptive Human Motion Style Transfer Method</strong><br>
    <strong>Jiafan Liu</strong><br>
    [<strong>Master Dissertation</strong>], 2025<br>
    <a href="https://dr.ntu.edu.sg/entities/publication/55bcfdb5-1276-45bf-aac5-355857bd9807">Paper</a>
  </div>
</div>

<div class="pub-block">
  <img class="pub-img" src="../images/paper_rethink.png" alt="Rethinking paper">
  <div class="pub-text">
    <strong>Rethinking Radiology Report Generation via Causal Inspired Counterfactual Augmentation.</strong><br>
    Xiao Song, <strong>Jiafan Liu</strong>, Yan Liu, Yun Li, Wenbin Lei, Ruxin Wang<br>
    ACM Conference on Bioinformatics, Computational Biology, and Health Informatics (<strong>ACM-BCB</strong>), 2024 &nbsp;<strong>(CCF-C Conference, student first author)</strong> &nbsp;<span class="oral-badge">(Oral)</span><br>
    <a href="https://dl.acm.org/doi/10.1145/3698587.3701353#abstract">Paper</a>
  </div>
</div>

<div class="pub-block">
  <img class="pub-img" src="../images/paper_patent.png" alt="Patent">
  <div class="pub-text">
    <strong>A Method for Cross-Domain Few-Shot Image Recognition Based Feature Transformation and Statistical Calibration</strong><br>
    Wei Luo, <strong>Jiafan Liu</strong><br>
    Patent Granted, 2023 &nbsp;<strong>(student first author)</strong>
  </div>
</div>

---

<div class="section-title">Education</div>

<div class="edu-block">
  <img class="edu-img" src="../images/NTU_logo.png" alt="NTU logo">
  <div class="edu-text">
    <strong>Nanyang Technological University</strong><br>
    Aug 2024 – June 2025<br>
    M.S. in Computer Control & Automation, School of Electrical and Electronic Engineering<br>
    <strong>GPA: 4.25 / 5.00 (Full Mark in EE6221, EE7204)</strong>
  </div>
</div>

<div class="edu-block">
  <img class="edu-img" src="../images/SCAU_logo.png" alt="SCAU logo">
  <div class="edu-text">
    <strong>South China Agricultural University</strong><br>
    Sept 2020 – June 2024<br>
    B.S. in Information System, School of Mathematics and Information<br>
    <strong>GPA: 91 / 100 (ranking: 1 in class)</strong>
  </div>
</div>

---

<div class="section-title">Internship</div>

<div class="edu-block">
  <img class="edu-img" src="../images/NTU_logo.png" alt="NTU logo">
  <div class="edu-text">
    <strong>Nanyang Technological University, <a href="https://www.ntu.edu.sg/rose">ROSE-Lab</a></strong><br>
    Research Intern &nbsp;|&nbsp; Aug 2024 – March 2025<br>
    Supervisor: Prof. Alex Kot<br>
    Research Direction: [CV, Motion Generation] Human Motion Style Transfer
  </div>
</div>

<div class="edu-block">
  <img class="edu-img" src="../images/West_logo.png" alt="Westlake logo">
  <div class="edu-text">
    <strong>Westlake University</strong><br>
    Research Intern &nbsp;|&nbsp; Feb 2024 – June 2024<br>
    Supervisor: Prof. Stan Z. Li, Dr. Cheng Tan<br>
    Research Direction: [CV, Video Generation] Spatio-temporal Video Prediction
  </div>
</div>

<div class="edu-block">
  <img class="edu-img" src="../images/SIAT_logo.jpg" alt="SIAT logo">
  <div class="edu-text">
    <strong>Shenzhen Institute of Advanced Technology, CAS</strong><br>
    Research Intern &nbsp;|&nbsp; Aug 2023 – Jan 2024<br>
    Supervisor: Prof. Ruxin Wang<br>
    Research Direction: [NLP, CV, Multi-Modality] Multimodal Medical Report Generation
  </div>
</div>

---

<div class="section-title">Awards</div>

- [2024] Outstanding Thesis Award
- [2022] National Innovation and Entrepreneurship Program **(Project Leader)**
- [2022] Outstanding Volunteer
- [2021 & 2022] SCAU Third-Class Scholarship