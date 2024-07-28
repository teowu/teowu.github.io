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

- 👋 Hi, I’m Teo Wu (*officially Haoning Wu*), Final Year PhD Candidate in Nanyang Technological University 🇸🇬, supervised by [Prof. Weisi Lin](https://personal.ntu.edu.sg/wslin/Home.html). Prior to that, I obtained by B.S. degree of computer science in Peking University, PR China. 

- I am currently focusing on multi-modal LLM (MLLM) pre-training and evaluation (longer context & better instruction-following). See our [**LongVideoBench**](https://https://longvideobench.github.io/), the first video benchmark for MLLMs proven improvable given more input frames (>=256). 

- 🌱 I have also been the lead of project [**Q-Future**: Visual Evaluation with MLLMs](https://github.com/Q-Future)📹, on which 5 first-authored papers accepted in top conferences including ICML, ICLR, CVPR, ECCV and ACMMM. The flagship scorer, [**OneAlign**](https://huggingface.co/q-future/one-align) has been downloaded more than 238K times (*until Jul 25, 2024*) on HuggingFace.

- Prior to MLLMs, my PhD topic was on *video quality assessment*, a traditional area trying to gauge the quality scores (and more) on videos. Among 6 papers published in that area (in ECCV, ICCV, TPAMI, *etc*), the two representative works are FAST-VQA [![](https://img.shields.io/github/stars/VQAssessment/FAST-VQA)](https://github.com/VQAssessment/FAST-VQA) and DOVER [![](https://img.shields.io/github/stars/VQAssessment/DOVER)](https://github.com/VQAssessment/DOVER), earning 1st and 2nd-ranked stars among all projects in [this topic](https://github.com/topics/video-quality-assessment). 

- 📫 Reach me by e-mail: realtimothyhwu@gmail.com/haoning001@e.ntu.edu.sg, Twitter: [Twitter](https://twitter.com/HaoningTimothy)
- [Google Scholar](https://scholar.google.com.hk/citations?user=wth-VbMAAAAJ&hl=en-US)

# 🔥 News

- *2024.07.16*: &nbsp;🎉🎉 4 papers in Q-Future get accepted by ACMMM (1 first-authored, 3 Oral)!
- *2024.07.02*: &nbsp;🎉🎉 Co-Instruct get accepted by ECCV2024 (score: 5543)! 
- *2024.05.02*: &nbsp;🎉🎉 Q-Align get accepted by ICML2024 (score: 7765)!
- *2024.02.27*: &nbsp;🎉🎉 Q-Instruct get accepted by CVPR2024!
- *2024.01.16*: &nbsp;🎉🎉 Q-Bench get accepted by ICLR2024 as a Spotlight paper!
- *2023.09.10*: &nbsp;🎉🎉 Extension of FAST-VQA (FasterVQA) get accepted by TPAMI (IF: 23.600)!
- *2023.07.26*: &nbsp;🎉🎉 MaxVQA get accepted by ACMMM2023 as an Oral paper (CCF-A)!
- *2023.07.14*: &nbsp;🎉🎉 DOVER get accepted by ICCV2023 (CCF-A)!
- *2023.02.28*: &nbsp;🎉🎉 DisCoVQA get accepted by TCSVT. *First paper written in my PhD career.*
- *2022.07.07*: &nbsp;🎉🎉 FAST-VQA get accepted by ECCV2022 (CCF-B)!

# 📝 Selected Publications

## Preprints


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><img src='https://longvideobench.github.io/static/images/curve.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[LongVideoBench: A Benchmark for Long-context Interleaved Video-Language Understanding](https://longvideobench.github.io) [![](https://img.shields.io/github/stars/longvideobench/LongVideoBench)](https://github.com/longvideobench/LongVideoBench)

- Authors: *me*, Dongxu, Bei Chen, Junnan
- TL, DR: A benchmark for **long** videos that truly requires a **long** input (*i.e.* hundreds of frames). First-ever non-synthetic benchmark (6.7K human-crafted MCQs) on long-context multi-modal understanding.

</div>
</div>

## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='https://raw.githubusercontent.com/Q-Future/Co-Instruct/main/co-instruct.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Open-ended Visual Quality Comparison](https://github.com/Q-Future/Co-Instruct) [![](https://img.shields.io/github/stars/Q-Future/Co-Instruct)](https://github.com/Q-Future/Co-Instruct)

- Authors: *me*, Hanwei, Zicheng, *et al.*
- TL, DR: The first work for MLLMs on visual quality comparison, via bootstrapping human and LLM, plus distilling GPT-4v. It is a very early attempt on multi-image MLLM. Proposed dataset has been integrated by LLaVA-Interleave and Mantis.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='https://raw.githubusercontent.com/Q-Future/Q-Align/main/fig/onescorer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Align: Teaching LMMs for Visual Scoring via Discrete Text-Defined Levels](https://github.com/Q-Future/Q-Align) [![](https://img.shields.io/github/stars/Q-Future/Q-Align)](https://github.com/Q-Future/Q-Align)


- Authors: *me*, Zicheng, *et al.*
- TL, DR: The best visual quality and aesthetic scorer so far (*disclaimer: until Jul 25, 2024*); Yet a better way to train LMMs on scoring. It fine-tunes an LMM with discrete text levels (*good, poor, fair*) and extract the weighted average of token probabilities for continuous scores on inference. SOTA on 12 datasets.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='https://raw.githubusercontent.com/Q-Future/Q-Instruct/main/new_q_instruct.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Instruct: Improving Low-level Visual Abilities for Multi-modality Foundation Models](https://github.com/Q-Future/Q-Instruct) [![](https://img.shields.io/github/stars/Q-Future/Q-Instruct)](https://github.com/Q-Future/Q-Instruct)


- Authors: *me*, Zicheng, Erli, *et al.*
- TL, DR: The first low-level visual instruction tuning dataset. Includes GPT to generate QA pairs based on human-annotated quality descriptions.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024 (Spotlight)</div><img src='https://github.com/Q-Future/Q-Bench/raw/master/qbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-Level Vision](https://github.com/Q-Future/Q-Bench) [![](https://img.shields.io/github/stars/Q-Future/Q-Bench)](https://github.com/Q-Future/Q-Bench)

- Authors: *me*, Zicheng, Erli, *et al.*
- TL, DR: The first-things-first of Q-Future, defining three important tasks: low-level description (similar to captioning), low-level question-answering, and scoring. It has been extended to multi-image versions ([Q-Bench+](https://arxiv.org/abs/2402.07116)) as well as on AI-generated artifacts ([A-Bench](https://arxiv.org/abs/2406.03070)). 

</div>
</div>


