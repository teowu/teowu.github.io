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

- 👋 Hi, I’m Teo (Timothy) Haoning Wu, Second Year PhD Student in Nanyang Technological University 🇸🇬, [Resume](https://github.com/teowu/teowu/raw/master/Resume.pdf)
- 🌱 I’m currently working on *efficient+explainable* [Video Quality Assessment](https://github.com/QualityAssessment)📹

- See my top Repos:
- - 🥇[DOVER](https://github.com/teowu/DOVER) TL,DR: the SOTA NR-VQA method, can predict disentangled aesthetic and technical quality. [Colab demo](https://colab.research.google.com/github/taskswithcode/DOVER/blob/master/TWCDOVER.ipynb) available.
- - 🧰[End-to-End VQA Toolbox (FAST-VQA)](https://github.com/teowu/FAST-VQA-and-FasterVQA) TL, DR: An end-to-end Video Quality Assessment toolbox allowing you to develop your methods; official repo for FAST-VQA [ECCV 2022](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660528.pdf)!
- 📫 Reach me by e-mail: realtimothyhwu@gmail.com, Twitter: [Twitter](https://twitter.com/HaoningTimothy)
- [Google Scholar](https://scholar.google.com.hk/citations?user=wth-VbMAAAAJ&hl=en-US)


# 🔥 News
- *2022.11*: &nbsp;🎉🎉 DOVER (the state-of-the-art on in-the-wild VQA) released its code, model, demo and preprint paper. 
- *2022.10*: &nbsp;🎉🎉 FAST-VQA published on Springer, its extension FasterVQA coming out. 

# 📝 Publications 

## Conference Proceedings

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='https://github.com/QualityAssessment/FAST-VQA-and-FasterVQA/raw/dev/demos/fastervqa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FAST-VQA: Efficient End-to-end Video Quality Assessment with Fragment Sampling](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660528.pdf)

**Haoning Wu**, Chaofeng Chen, Jingwen Hou, Liang Liao, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/QualityAssessment/FAST-VQA-and-FasterVQA) [![](https://img.shields.io/github/stars/QualityAssessment/FAST-VQA-and-FasterVQA)](https://github.com/QualityAssessment/FAST-VQA-and-FasterVQA),  [**ArXiv**](https://arxiv.org/abs/2207.02595),  [**Extension (Under Review for TPAMI)**](https://arxiv.org/abs/2210.05357)
  
- Consisting of fragments and FANet, the proposed FrAgment Sample Transformer for VQA (**FAST-VQA**) enables efficient end-to-end deep VQA and learns effective video-quality-related representations. It improves state-of-the-art accuracy by around 10% while reducing 99.5% FLOPs on 1080P high-resolution videos.
- In our extension, we propose a unified scheme, spatial-temporal grid mini-cube sampling (St-GMS) and the most efficient NR-VQA method at present, **FasterVQA**. FasterVQA achieve significantly better performance than existing approaches on all VQA benchmarks while requiring only 1/1612 FLOPs compared to the current state-of-the-art.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2022 (Oral)</div><img src='https://github.com/teowu/teowu.github.io/raw/main/images/tpqi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring the Effectiveness of Video Perceptual Representation in Blind Video Quality Assessment](https://dl.acm.org/doi/abs/10.1145/3503161.3547849)

Liang Liao, Kangmin Xu, **Haoning Wu**, Chaofeng Chen, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/UoLMM/TPQI-VQA),  [**ArXiv**](https://arxiv.org/abs/2207.03723),  **Extension (Under Review for TPAMI)** （coming soon)
  
-  Experiments show that the perceptual representation in the HVS is an effective way of predicting subjective temporal quality, and thus **TPQI** can, for the first time, achieve comparable performance to the spatial quality metric and be even more effective in assessing videos with large temporal variations.
</div>
</div>

## Preprints


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://github.com/teowu/teowu.github.io/raw/main/images/dover.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Disentangling Aesthetic and Technical Effects in Video Quality Assessment of User Generated Content](https://github.com/QualityAssessment/DOVER)
  
**Haoning Wu**, Liang Liao, Chaofeng Chen, Jingwen Hou, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/QualityAssessment/DOVER) [![](https://img.shields.io/github/stars/QualityAssessment/DOVER)](https://github.com/QualityAssessment/DOVER),  [**ArXiv**](https://arxiv.org/abs/2211.04894)
  
- The proposed Disentangled Objective Video Quality Evaluator (**DOVER**) reach excellent performance (0.91 SRCC for KoNViD-1k, 0.89 SRCC for LSVQ, 0.88 SRCC for YouTube-UGC) in the UGC-VQA problem. More importantly, our blind subjective studies prove that the separate evaluators in DOVER can effectively match human perception on respective disentangled quality issues.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://github.com/teowu/teowu.github.io/raw/main/images/discovqa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DisCoVQA: Temporal Distortion-Content Transformers for Video Quality Assessment](https://github.com/QualityAssessment/DisCoVQA)
  
**Haoning Wu**, Chaofeng Chen, Liang Liao, Jingwen Hou, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/QualityAssessment/DisCoVQA),  [**ArXiv**](https://arxiv.org/abs/2206.09853)
  
- Based on prominent time-series modeling ability of transformers, we propose a novel and effective transformer-based VQA method to tackle temporal distortions as well as the content-related temporal attention mechanism. Without extra data for pre-training, the DisCoVQA reaches state-of-the-art performance on several VQA benchmarks and up to 10% better generalization ability than existing methods.
</div>
</div>



# 📖 Educations
- *2021.08 - (now)*, PhD Student, S-Lab, Nanyang Technological University, supervised by [Prof. Weisi Lin](https://personal.ntu.edu.sg/wslin/Home.html).
- *2017.09 - 2021.07*, B.S. in Computer Science, EECS, Peking University. 



# 💻 Internships
- *2022.01 - 2022.08*, Sensetime Research, Beijing, China.
- *2021.05 - 2021.08*, AiFi Inc, CA, USA.
- *2020.06 - 2021.03*, Megvii Research, Beijing, China.
