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

- 👋 Hi, I’m Teo (Timothy) Wu, Final Year PhD Candidate in Nanyang Technological University 🇸🇬, [Resume](https://github.com/teowu/teowu/blob/master/2024resume.pdf), [Homepage](https://teowu.github.io)
- 🌱 I’m currently working on project [**Q-Future**: Visual Evaluation with Foundation Models](https://github.com/Q-Future)📹

- See my top Repos:
- - ⚖️[**Q-Align**](https://q-align.github.io): A **text-guided syllabus** to teach multi-modality foundational models for most accurate visual rating ever! See its 📖[paper](https://q-future.github.io/Q-Align/fig/Q_Align_v0_1_preview.pdf) and 🖥️[repository](https://github.com/Q-Future/Q-Align)~
- - 🧑‍🏫[**Q-Instruct**](https://github.com/Q-Future/Q-Instruct): A **dataset** and a **model zoo** for multi-modality foundational models with improved abilities on low-level vision and visual quality assessment! See its 📖[paper](https://q-future.github.io/Q-Instruct/fig/Q_Instruct_v0_1_preview.pdf) and 🖥️[repository](https://github.com/Q-Future/Q-Instruct)~
- - 📑[ICLR 2024 Spotlight, **Q-Bench**](https://github.com/Q-Future/Q-Bench): A benchmark for multi-modality LLMs on low-level vision and visual quality assessment! See its 📖[paper](https://arxiv.org/abs/2309.14181) and 🖥️[repository](https://github.com/Q-Future/Q-Bench)~
- - [ACMMM 2023 Oral, MaxVQA/MaxWell](https://github.com/VQAssessment/MaxVQA) TL,DR: 16-dimensional VQA Dataset and Method, towards explainable VQA. Gradio demos are available in repo.
- - 🥇 [ICCV 2023, DOVER](https://github.com/VQAssessment/DOVER) TL,DR: the SOTA NR-VQA method, can predict disentangled aesthetic and technical quality. [Colab demo](https://colab.research.google.com/github/taskswithcode/DOVER/blob/master/TWCDOVER.ipynb) available.
- - 🧰 [TPAMI 2023, ECCV 2022, End-to-End VQA Toolbox (FAST-VQA)](https://github.com/VQAssessment/FAST-VQA-and-FasterVQA) TL, DR: An end-to-end Video Quality Assessment toolbox allowing you to develop your methods; official repo for [FAST-VQA](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660528.pdf) and [FasterVQA](https://ieeexplore.ieee.org/document/10264158)!
- - 🥇 [ICME 2023 Oral, Zero-Shot BVQI](https://github.com/VQAssessment/BVQI) TL, DR: the SOTA zero-shot NR-VQA method.
- 📫 Reach me by e-mail: realtimothyhwu@gmail.com, Twitter: [Twitter](https://twitter.com/HaoningTimothy)
- [Google Scholar](https://scholar.google.com.hk/citations?user=wth-VbMAAAAJ&hl=en-US)


# 🔥 News
- *2024.01.16*: &nbsp;🎉🎉 Q-Bench get accepted by ICLR2024 as a Spotlight paper!
- *2023.09.10*: &nbsp;🎉🎉 Extension of FAST-VQA (FasterVQA) get accepted by TPAMI (IF: 23.600)!
- *2023.07.27*: &nbsp;🎉🎉 Passed my PhD Qualification Examination, now I am a PhD candidate!
- *2023.07.26*: &nbsp;🎉🎉 MaxVQA get accepted by ACMMM2023 as an Oral paper (CCF-A)!
- *2023.07.14*: &nbsp;🎉🎉 DOVER get accepted by ICCV2023 (CCF-A)!
- *2023.07.11*: &nbsp;🎉🎉 BUONA-VISTA get **oral** presentation in ICME2023 (CCF-B)!
- *2023.03.12*: &nbsp;🎉🎉 BUONA-VISTA get accepted by ICME2023 (CCF-B)!
- *2023.02.28*: &nbsp;🎉🎉 DisCoVQA get accepted by TCSVT2023 (IF: 8.400)!
- *2022.07.07*: &nbsp;🎉🎉 FAST-VQA get accepted by ECCV2022 (CCF-B)!

# 📝 Publications 

## Research Spotlight!

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://raw.githubusercontent.com/Q-Future/Q-Align/main/fig/onescorer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Align: Teaching LMMs for Visual Scoring via Discrete Text-Defined Levels](https://github.com/Q-Future/Q-Align) [![](https://img.shields.io/github/stars/Q-Future/Q-Align)](https://github.com/Q-Future/Q-Align)

**Haoning Wu**\*+, Zicheng Zhang\*, Weixia Zhang, Chaofeng Chen, Liang Liao, Chunyi Li, Yixuan Gao, Annan Wang, Erli Zhang, Kaixin Xu, Wenxiu Sun, Qiong Yan, Xiongkuo Min, Guangtao Zhai, Weisi Lin

- We prove that **discrete text-defined rating levels** (*excellent/good/fair/poor/bad*) are more effective than scores themselves in teaching multi-modality foundation models to score.
- Without any additional design, it reaches state-of-the-art performance on IQA, IAA and VQA with remarkable gain! And it unifies these three tasks (mixing 5 training datasets) in one model (**OneAlign**), click the following link and try:
- <a href="https://huggingface.co/spaces/teowu/OneScorer"><img src="https://huggingface.co/datasets/huggingface/badges/raw/main/open-in-hf-spaces-sm-dark.svg" alt="Open in Huggingface Spaces"></a>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://raw.githubusercontent.com/Q-Future/Q-Instruct/main/new_q_instruct.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Instruct: Improving Low-level Visual Abilities for Multi-modality Foundation Models](https://github.com/Q-Future/Q-Instruct) [![](https://img.shields.io/github/stars/Q-Future/Q-Instruct)](https://github.com/Q-Future/Q-Instruct)

**Haoning Wu**\*, Zicheng Zhang\*, Erli Zhang\*, Chaofeng Chen, Liang Liao, Annan Wang, Kaixin Xu, Chunyi Li, Jingwen Hou, Guangtao Zhai, Xue Geng, Wenxiu Sun, Qiong Yan, Weisi Lin

- We propose the **Q-Instruct**, a 200K instruction-tuning dataset for low-level vision, derived from a self-collected database on 58K real human pathway feedbacks on image quality.
- The Q-Instruct significantly improves the low-level perceptual accuracy of MLLMs (e.g. LLaVA-v1.5-7B), and we have released the **[model zoo](https://q-future.github.com/Q-Instruct/model_zoo)**. Run them on our local machines!
- <a href="https://huggingface.co/spaces/teowu/Q-Instruct-on-mPLUG-Owl-2"><img src="https://huggingface.co/datasets/huggingface/badges/raw/main/open-in-hf-spaces-sm-dark.svg" alt="Open in Huggingface Spaces"></a>

</div>
</div>


## Publications


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024 (Spotlight)</div><img src='https://github.com/Q-Future/Q-Bench/raw/master/qbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-Level Vision](https://github.com/Q-Future/Q-Bench) [![](https://img.shields.io/github/stars/Q-Future/Q-Bench)](https://github.com/Q-Future/Q-Bench)

**Haoning Wu**\*, Zicheng Zhang\*, Erli Zhang\*, Chaofeng Chen, Liang Liao, Annan Wang, Chunyi Li, Wenxiu Sun, Qiong Yan, Guangtao Zhai, Weisi Lin


- We construct the **Q-Bench**, a benchmark to examine the progresses of MLLMs on lowlevel visual abilities. Anticipating these large foundation models to be general-purpose intelligence that can ultimately relieve human efforts, we propose that MLLMs should achieve three important and distinct abilities: perception on low-level visual attributes, language description on low-level visual information, as well as IQA.
- Submit your model at [our project page](https://github.com/VQAssessment/Q-Bench/) to compete with existing ones!

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2023 (IF: 23.60), ECCV 2022</div><img src='https://github.com/VQAssessment/FAST-VQA-and-FasterVQA/raw/dev/demos/fastervqa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neighbourhood Representative Sampling for Efficient End-to-End Video Quality Assessment](https://ieeexplore.ieee.org/document/10264158)

**Haoning Wu**, Chaofeng Chen, Jingwen Hou, Liang Liao, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/FAST-VQA-and-FasterVQA) [![](https://img.shields.io/github/stars/VQAssessment/FAST-VQA-and-FasterVQA)](https://github.com/VQAssessment/FAST-VQA-and-FasterVQA),  [**ArXiv**](https://arxiv.org/abs/2207.02595)
  
- Consisting of fragments and FANet, the proposed FrAgment Sample Transformer for VQA (**FAST-VQA**) enables efficient end-to-end deep VQA and learns effective video-quality-related representations. It improves state-of-the-art accuracy by around 10% while reducing 99.5% FLOPs on 1080P high-resolution videos.
- In our extension, we propose a unified scheme, spatial-temporal grid mini-cube sampling (St-GMS) and the most efficient NR-VQA method at present, **FasterVQA**. FasterVQA achieve significantly better performance than existing approaches on all VQA benchmarks while requiring only 1/1612 FLOPs compared to the current state-of-the-art.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2023 (Oral)</div><img src='https://github.com/VQAssessment/MaxVQA/raw/master/figs/maxwell.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Explainable Video Quality Assessment: A Database and a Language-Prompted Approach](https://github.com/VQAssessment/MaxVQA)
  
**Haoning Wu**\*, Erli Zhang\*, Liang Liao, Chaofeng Chen, Jingwen Hou, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/MaxVQA) [![](https://img.shields.io/github/stars/VQAssessment/MaxVQA)](https://github.com/VQAssessment/MaxVQA),  [**ArXiv**](https://arxiv.org/abs/2305.12726)
  
- We collect over two million human opinions on 13 dimensions of quality-related factors to establish the multi-dimensional Maxwell database. Furthermore, we propose the MaxVQA, a language-prompted VQA approach that modifies CLIP to better capture important quality issues as observed in our analyses. 
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
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2023 (IF: 8.400)</div><img src='https://github.com/teowu/teowu.github.io/raw/main/images/discovqa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DisCoVQA: Temporal Distortion-Content Transformers for Video Quality Assessment](https://github.com/VQAssessment/DisCoVQA)
  
**Haoning Wu**, Chaofeng Chen, Liang Liao, Jingwen Hou, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/DisCoVQA),  [**ArXiv**](https://arxiv.org/abs/2206.09853)
  
- Based on prominent time-series modeling ability of transformers, we propose a novel and effective transformer-based VQA method to tackle temporal distortions as well as the content-related temporal attention mechanism. Without extra data for pre-training, the DisCoVQA reaches state-of-the-art performance on several VQA benchmarks and up to 10% better generalization ability than existing methods.
</div>
</div>


# 📖 Educations

- *2021.07.27 - 2024.07.31 (expected)*, PhD Candidate, S-Lab, Nanyang Technological University, supervised by [Prof. Weisi Lin](https://personal.ntu.edu.sg/wslin/Home.html), Research Topic: Consistent and Robust Video Quality Assessments.
- *2021.08.10 - 2023.07.27*, PhD Student, S-Lab, Nanyang Technological University, supervised by [Prof. Weisi Lin](https://personal.ntu.edu.sg/wslin/Home.html).
- *2017.09 - 2021.07*, B.S. in Computer Science, EECS, Peking University. 

# 📖 Teachings
- 2023.02 - 2023.05, Teaching Assistant for SC1015: Introduction to Data Science and Artificial Intelligence.
- 2023.08 - 2024.05, Teaching Assistant for SC3000: Artificial Intelligence.

# 💻 Internships
- *2023.05 - 2023.08*, TikTok Pte Ltd, Singapore, Singapore.
- *2022.01 - 2022.08*, Sensetime Research, Beijing, China.
- *2021.05 - 2021.08*, AiFi Inc, CA, USA.
- *2020.06 - 2021.03*, Megvii Research, Beijing, China.
