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

- 👋 Hi, I’m Teo (Timothy) Wu, PhD Candidate in Nanyang Technological University 🇸🇬, [Resume](https://github.com/teowu/teowu/blob/master/Resume.pdf), [Homepage](https://teowu.github.io)
- 🌱 I’m currently working on *efficient+explainable* [Video Quality Assessment](https://github.com/VQAssessment)📹

Star our repos if you are interested!!!
[![Star History Chart](https://api.star-history.com/svg?repos=VQAssessment/DOVER,VQAssessment/FAST-VQA-and-FasterVQA&type=Timeline)](https://star-history.com/#VQAssessment/DOVER&VQAssessment/FAST-VQA-and-FasterVQA&Timeline)

- See my top Repos:
- - [ACMMM 2023, MaxVQA/MaxWell](https://github.com/VQAssessment/MaxVQA) TL,DR: 16-dimensional VQA Dataset and Method, towards explainable VQA. Gradio demos are available in repo.
- - 🥇 [ICCV 2023, DOVER](https://github.com/VQAssessment/DOVER) TL,DR: the SOTA NR-VQA method, can predict disentangled aesthetic and technical quality. [Colab demo](https://colab.research.google.com/github/taskswithcode/DOVER/blob/master/TWCDOVER.ipynb) available.
- - 🧰 [ECCV 2022, End-to-End VQA Toolbox (FAST-VQA)](https://github.com/VQAssessment/FAST-VQA-and-FasterVQA) TL, DR: An end-to-end Video Quality Assessment toolbox allowing you to develop your methods; official repo for [FAST-VQA](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660528.pdf)!
- - 🥇 [ICME 2023 Oral, Zero-Shot BVQI](https://github.com/VQAssessment/BVQI) TL, DR: the SOTA zero-shot NR-VQA method.
- 📫 Reach me by e-mail: realtimothyhwu@gmail.com, Twitter: [Twitter](https://twitter.com/HaoningTimothy)
- [Google Scholar](https://scholar.google.com.hk/citations?user=wth-VbMAAAAJ&hl=en-US)


# 🔥 News
- *2023.07.27*: &nbsp;🎉🎉 Passed my PhD Qualification Examination, now I am a PhD candidate!
- *2023.07.26*: &nbsp;🎉🎉 MaxVQA get accepted by ACMMM2023 (CCF-A)!
- *2023.07.14*: &nbsp;🎉🎉 DOVER get accepted by ICCV2023 (CCF-A)!
- *2023.07.11*: &nbsp;🎉🎉 BUONA-VISTA get **oral** presentation in ICME2023 (CCF-B)!
- *2023.03.12*: &nbsp;🎉🎉 BUONA-VISTA get accepted by ICME2023 (CCF-B)!
- *2023.02.28*: &nbsp;🎉🎉 DisCoVQA get accepted by TCSVT2023 (IF: 8.400)!
- *2022.07.07*: &nbsp;🎉🎉 FAST-VQA get accepted by ECCV2022 (CCF-B)!

# 📝 Publications 

## Conference Proceedings

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2023</div><img src='https://github.com/VQAssessment/MaxVQA/blob/master/figs/maxwell.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Explainable Video Quality Assessment: A Database and a Language-Prompted Approach](https://github.com/VQAssessment/MaxVQA)
  
**Haoning Wu**\*, Erli Zhang\*, Liang Liao, Chaofeng Chen, Jingwen Hou, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/MaxVQA) [![](https://img.shields.io/github/stars/VQAssessment/MaxVQA)](https://github.com/VQAssessment/MaxVQA),  [**ArXiv**](https://arxiv.org/abs/2305.12726)
  
- We collect over two million opinions on 4,543 in-the-wild videos on 13 dimensions of quality-related factors, including in-capture authentic distortions (e.g. motion blur, noise, flicker), errors introduced by compression and transmission, and higher-level experiences on semantic contents and aesthetic issues (e.g. composition, camera trajectory), to establish the multi-dimensional Maxwell database. Furthermore, we propose the MaxVQA, a language-prompted VQA approach that modifies vision-language foundation model CLIP to better capture important quality issues as observed in our analyses. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='https://github.com/teowu/teowu.github.io/raw/main/images/dover.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Video Quality Assessment on User Generated Contents from Aesthetic and Technical Perspectives](https://github.com/VQAssessment/DOVER)
  
**Haoning Wu**\*, Erli Zhang\*, Liang Liao\*, Chaofeng Chen, Jingwen Hou, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/DOVER) [![](https://img.shields.io/github/stars/VQAssessment/DOVER)](https://github.com/VQAssessment/DOVER),  [**ArXiv**](https://arxiv.org/abs/2211.04894v3)
  
- The proposed Disentangled Objective Video Quality Evaluator (**DOVER**) reach state-of-the-art performance (0.91 SRCC for KoNViD-1k, 0.89 SRCC for LSVQ, 0.89 SRCC for YouTube-UGC) in the UGC-VQA problem. More importantly, our subjective studies construct the first aesthetic and technical VQA database, the DIVIDE-3k, proving that UGC-VQA is jointly affected by the two perspectives.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2023 (Oral)</div><img src='https://github.com/VQAssessment/BVQI/raw/master/figs/bvqiplus.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Opinion-unaware Video Quality Assessment with Semantic Affinity Criterion](https://github.com/VQAssessment/BVQI)

[**GitHub**](https://github.com/VQAssessment/BVQI) [![](https://img.shields.io/github/stars/VQAssessment/BVQI)](https://github.com/VQAssessment/BVQI),  [**ArXiv (Short Version)**](https://arxiv.org/abs/2302.13269), [**Extension (Under Review for TIP)**](https://arxiv.org/abs/2304.14672)

- Robustly predict quality without training from any MOS scores.
- Localized quality prediction via CLIP.
- Given a small set of MOS-labelled videos, can robustly+efficiently fine-tune on them.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='https://github.com/VQAssessment/FAST-VQA-and-FasterVQA/raw/dev/demos/fastervqa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FAST-VQA: Efficient End-to-end Video Quality Assessment with Fragment Sampling](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660528.pdf)

**Haoning Wu**, Chaofeng Chen, Jingwen Hou, Liang Liao, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/FAST-VQA-and-FasterVQA) [![](https://img.shields.io/github/stars/VQAssessment/FAST-VQA-and-FasterVQA)](https://github.com/VQAssessment/FAST-VQA-and-FasterVQA),  [**ArXiv**](https://arxiv.org/abs/2207.02595),  [**Extension (Under Review for TPAMI)**](https://arxiv.org/abs/2210.05357)
  
- Consisting of fragments and FANet, the proposed FrAgment Sample Transformer for VQA (**FAST-VQA**) enables efficient end-to-end deep VQA and learns effective video-quality-related representations. It improves state-of-the-art accuracy by around 10% while reducing 99.5% FLOPs on 1080P high-resolution videos.
- In our extension, we propose a unified scheme, spatial-temporal grid mini-cube sampling (St-GMS) and the most efficient NR-VQA method at present, **FasterVQA**. FasterVQA achieve significantly better performance than existing approaches on all VQA benchmarks while requiring only 1/1612 FLOPs compared to the current state-of-the-art.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2023 (IF: 8.400)</div><img src='https://github.com/teowu/teowu.github.io/raw/main/images/discovqa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2022 (Oral)</div><img src='https://github.com/teowu/teowu.github.io/raw/main/images/tpqi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring the Effectiveness of Video Perceptual Representation in Blind Video Quality Assessment](https://dl.acm.org/doi/abs/10.1145/3503161.3547849)

Liang Liao, Kangmin Xu, **Haoning Wu**, Chaofeng Chen, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub (Integrated into BVQI)**](https://github.com/VQAssessment/BVQI),  [**ArXiv**](https://arxiv.org/abs/2207.03723)
  
-  Experiments show that the perceptual representation in the HVS is an effective way of predicting subjective temporal quality, and thus **TPQI** can, for the first time, achieve comparable performance to the spatial quality metric and be even more effective in assessing videos with large temporal variations.
</div>
</div>

## Journals and Transactions

[DisCoVQA: Temporal Distortion-Content Transformers for Video Quality Assessment](https://github.com/VQAssessment/DisCoVQA)
  
**Haoning Wu**, Chaofeng Chen, Liang Liao, Jingwen Hou, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/DisCoVQA),  [**ArXiv**](https://arxiv.org/abs/2206.09853)
  
- Based on prominent time-series modeling ability of transformers, we propose a novel and effective transformer-based VQA method to tackle temporal distortions as well as the content-related temporal attention mechanism. Without extra data for pre-training, the DisCoVQA reaches state-of-the-art performance on several VQA benchmarks and up to 10% better generalization ability than existing methods.
</div>
</div>



# 📖 Educations
- *2021.07.27 - 2024.08.08 (expected)*, PhD Candidate, S-Lab, Nanyang Technological University, supervised by [Prof. Weisi Lin](https://personal.ntu.edu.sg/wslin/Home.html), Research Topic: Consistent and Robust Video Quality Assessments.
- *2021.08.10 - 2023.07.27 (now)*, PhD Student, S-Lab, Nanyang Technological University, supervised by [Prof. Weisi Lin](https://personal.ntu.edu.sg/wslin/Home.html).
- *2017.09 - 2021.07*, B.S. in Computer Science, EECS, Peking University. 

# 📖 Teachings
- 2023.02 - 2023.05, Teaching Assistant for SC1015: Introduction to Data Science and Artificial Intelligence.

# 💻 Internships
- *2023.05 - 2023.08*, TikTok Pte Ltd, Singapore, Singapore.
- *2022.01 - 2022.08*, Sensetime Research, Beijing, China.
- *2021.05 - 2021.08*, AiFi Inc, CA, USA.
- *2020.06 - 2021.03*, Megvii Research, Beijing, China.
