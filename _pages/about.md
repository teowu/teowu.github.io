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

- 👋 Hi, I’m Teo Wu (*officially Haoning Wu*), working on LMMs in [Rhymes AI](https://rhymes.ai), closely advised by [Dongxu Li](https://https://sites.google.com/view/dongxu-li/home) and [Junnan Li](https://openreview.net/profile?id=~Junnan_Li2). Prior to this, I have been a PhD candidate (preparing thesis defense) in Nanyang Technological University 🇸🇬, supervised by [Prof. Weisi Lin](https://personal.ntu.edu.sg/wslin/Home.html). I obtained by B.S. degree of computer science in Peking University (北京大学).

- I am currently focusing on LMM pre-training and evaluation (video & longer context & better instruction-following). See our [**LongVideoBench**](https://longvideobench.github.io/), the first video benchmark for LMMs proven improvable given more input frames (>=256). I have also contributed to video and long-context training of **Aria** ([Model](https://huggingface.co/rhymes-ai/Aria), [Paper](https://huggingface.co/papers/2410.05993), [GitHub](https://github.com/rhymes-ai/Aria)), an excellent open-source native MoE LMM with abilities matching GPT-4o-mini/Gemini-1.5-Flash in only 3.9B activated parameters.

- 🌱 I have also been the lead of project [**Q-Future**: Visual Evaluation with LMMs](https://github.com/Q-Future)📹, on which 7 first-authored papers accepted in top conferences and journels including ICML, ICLR, NeurIPS, TPAMI, CVPR, ECCV and ACMMM. The flagship scorer, [**OneAlign**](https://huggingface.co/q-future/one-align) has been downloaded more than 238K times (*until Jul 25, 2024*) on HuggingFace.

- Prior to LMMs, my PhD topic was on *video quality assessment*, a traditional area trying to gauge the quality scores (and more) on videos. Among 6 papers published in that area (in ECCV, ICCV, TPAMI, *etc*), the two representative works are FAST-VQA and DOVER, which have been most-used baselines in that field.

- 📫 Reach me by e-mail: realtimothyhwu@gmail.com/haoning001@e.ntu.edu.sg, Twitter: [Twitter](https://twitter.com/HaoningTimothy)
- [Google Scholar](https://scholar.google.com.hk/citations?user=wth-VbMAAAAJ&hl=en-US)

# 🔥 News

- *2024.10.11*: &nbsp;🎉🎉 We release [Aria](https://huggingface.co/rhymes.ai/Aria), a native LMM that excels on text, code, image, video, PDF and more!
- *2024.09.26*: &nbsp;🎉🎉 LongVideoBench get accepted by Neurips2024 D&B track!
- *2024.09.26*: &nbsp;🎉🎉 Compare2Score get accepted by Neurips2024 as Spotlight!
- *2024.08.08*: &nbsp;🎉🎉 Extension of Q-Bench (Q-Bench+, on image pairs) get accepted by TPAMI!
- *2024.07.16*: &nbsp;🎉🎉 4 papers in Q-Future get accepted by ACMMM (1 first-authored, 3 Oral)!
- *2024.07.02*: &nbsp;🎉🎉 Co-Instruct get accepted by ECCV2024 as an Oral paper!
- *2024.05.02*: &nbsp;🎉🎉 Q-Align get accepted by ICML2024 (score: 7765)!
- *2024.02.27*: &nbsp;🎉🎉 Q-Instruct get accepted by CVPR2024!
- *2024.01.16*: &nbsp;🎉🎉 Q-Bench get accepted by ICLR2024 as a Spotlight paper!
- *2023.09.10*: &nbsp;🎉🎉 Extension of FAST-VQA (FasterVQA) get accepted by TPAMI!
- *2023.07.26*: &nbsp;🎉🎉 MaxVQA get accepted by ACMMM2023 as an Oral paper!
- *2023.07.14*: &nbsp;🎉🎉 DOVER get accepted by ICCV2023!
- *2023.02.28*: &nbsp;🎉🎉 DisCoVQA get accepted by TCSVT. *First paper written in my PhD career.*
- *2022.07.07*: &nbsp;🎉🎉 FAST-VQA get accepted by ECCV2022!



# 📝 Selected Publications


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurips 2024 D&B</div><img src='https://longvideobench.github.io/static/images/curve.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[LongVideoBench: A Benchmark for Long-context Interleaved Video-Language Understanding](https://longvideobench.github.io) [![](https://img.shields.io/github/stars/longvideobench/LongVideoBench)](https://github.com/longvideobench/LongVideoBench)

- Authors: *me*, Dongxu, Bei Chen, Junnan
- TL, DR: A benchmark for **long** videos that truly requires a **long** input (*i.e.* hundreds of frames). First-ever non-synthetic benchmark (6.7K human-crafted MCQs) on long-context multi-modal understanding.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024 (Oral)</div><img src='https://raw.githubusercontent.com/Q-Future/Co-Instruct/main/co-instruct.png' alt="sym" width="100%"></div></div>
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


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024 (Spotlight) & TPAMI 2024</div><img src='https://github.com/Q-Future/Q-Bench/raw/master/qbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-Level Vision](https://github.com/Q-Future/Q-Bench) [![](https://img.shields.io/github/stars/Q-Future/Q-Bench)](https://github.com/Q-Future/Q-Bench)

- Authors: *me*, Zicheng, Erli, *et al.*
- TL, DR: The first-things-first of Q-Future, defining three important tasks: low-level description (similar to captioning), low-level question-answering, and scoring. It has been extended to multi-image versions ([Q-Bench+](https://arxiv.org/abs/2402.07116)) as well as on AI-generated artifacts ([A-Bench](https://arxiv.org/abs/2406.03070)). 

</div>
</div>


