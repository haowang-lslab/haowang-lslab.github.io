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

Hi! I am a 3rd-year undergraduate at <strong>Zhiyuan College (Honor, Top 10%), Shanghai Jiao Tong University</strong>.
My academic journey has been enriched by several research experiences.
Most recently, I was a research intern at <strong>National University of Singapore</strong>, collaborating with <a href="https://www.zhaominwu.com/">Dr. Zhaomin Wu</a> under the supervision of <a href="https://www.comp.nus.edu.sg/~hebs/">Prof. Bingsheng He</a>.
Before that, I worked as an undergraduate researcher at Shanghai Jiao Tong University, working alongside <a href="https://zhxie.site/">Mr. Zhihui Xie</a>, mentored by <a href="https://shuaili8.github.io/">Prof. Shuai Li</a> and <a href="https://scholar.google.com/citations?user=6-ARmXsAAAAJ">Dr. Tong Yu</a>.
I've also had the privilege of collaborating with <a href="https://bcmi.sjtu.edu.cn/~blu/">Prof. Bao-Liang Lu</a> and <a href="https://weilongzheng.github.io/">Prof. Wei-Long Zheng</a>.

Besides research, I've excelled in competitive programming, winning awards in OI, ICPC, CCPC and various other contests. See my <a href="assets/pdf/CV_Jizhou_Guo.pdf">CV</a> for details.

My research interests are primarily focused on Large Language Models and AI for Science. I'm always eager to engage in discussions about these topics, so please feel free to reach out if you'd like to chat!

# 🔥 News
- *2024.10*: &nbsp; Our work <a href="https://arxiv.org/abs/2410.10481">Model-Based Differentially Private Knowledge Transfer for Large Language Models</a> is on arXiv!
- *2024.09*: &nbsp; Our work <a href="https://arxiv.org/abs/2405.18711">Calibrating Reasoning in Language Models with Internal Consistency </a> is accepted to NeurIPS 2024! 🎉
- *2024.05*: &nbsp; Our work <a href="https://arxiv.org/abs/2405.18711">Calibrating Reasoning in Language Models with Internal Consistency </a> is on arXiv!

# 📝 Publications 
_<sup>*</sup> denotes equal contribution_

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/dp_knowledge_transfer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Model-Based Differentially Private Knowledge Transfer for Large Language Models](https://arxiv.org/abs/2410.10481)

Zhaomin Wu*, **Jizhou Guo**\*, Junyi Hou, Bingsheng He, Lixin Fan, Qiang Yang

- Proposed **Llamdex**, a novel framework that integrates privacy-preserving, domain-specific models into LLMs.
- Demonstrated significant performance gains in domain-specific tasks, with up to 26% accuracy improvement while maintaining differential privacy guarantees.
- Achieved comparable inference efficiency to base LLMs while enhancing domain-specific capabilities.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/internal_consistency.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Calibrating Reasoning in Language Models with Internal Consistency](https://arxiv.org/pdf/2405.18711)

Zhihui Xie, **Jizhou Guo**, Tong Yu, Shuai Li

- Developed a novel "internal consistency" approach to calibrate reasoning in Large Language Models (LLMs), resulting in a significant boost in reasoning performance.
- Conducted in-depth analysis of Chain-of-Thought (CoT) reasoning in LLMs through the lens of internal representations. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/eeg.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

EEG-based Emotion Recognition in an Olfactory Stimulation Paradigm

Jiaqi Wang, Zhengting Chen, Yifan Wu, Keyan Huang, Dian Zhang, **Jizhou Guo**, Xinglan Liu, Dan Peng, Weilong Zheng, Baoliang Lu

- Designed and executed experiments to predict human emotions from EEG signals under various olfactory stimuli.
- Implemented and compared multiple deep learning models (MLP, CNN, Transformer) with Domain-Adversarial Neural Networks (DANN).

</div>
</div>

# 💻 Projects

<div class='paper-box'><div class='paper-box-image'><div><img src='images/AD_bio.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Novel biological dressing for atopic dermatitis

- Work done at Quantitative Biology Summer School of Center for Life Sciences, Peking University on 2023.07.
- Conceptualized and simulated a novel bio-responsive bandage using MATLAB, modeling drug diffusion processes for optimized wound healing.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/spiderman.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Palm liveness detection

- Work done at Tencent Spark Project of Tencent Corporation on 2022.08.
- Engineered a robust palm liveness detection system.

</div>
</div>

# 🎖 Honors and Awards
- *2023.09* Merit Student in the Student Community (<strong>Among 19 SJTU undergraduate and graduate recipients</strong>).
- *2023.12* Second-Class Academic Scholarship, SJTU (<strong>Top 5%, ranked 2nd overall</strong>).
- *2023.12* Zhiyuan Honors Scholarship, SJTU.
- *2023.12* <strong> Third prize </strong> in Mathematics competition of Chinese College Students (Shanghai).
- *2023.09* <strong> First prize </strong> in Shanghai Collegiate Programming Contest (<strong>Ranked 2nd in Shanghai</strong>).
- *2023.08* <strong> Gold medal </strong> in Astar Programming Contest (Shanghai region) (<strong>Ranked 2nd in Shanghai</strong>).
- *2023.05* <strong> Gold medal </strong> in 2023 China Collegiate Programming Contest (<strong>CCPC</strong>) National Invitational Contest (Hunan).  
- *2023.05* <strong> Gold medal </strong> in 2023 International Collegiate Programming Contest (<strong>ICPC</strong>) Xi'an Invitational Contest.
- *2022.12* Zhiyuan Honors Scholarship, SJTU.
- *2022.12* <strong> Gold medal </strong> in 2022 International Collegiate Programming Contest (<strong>ICPC</strong>) Asia Hangzhou Regional Contest (<strong>Ranked 8th nationwide</strong>).
- *2022.09* <strong> Gold medal </strong> in 2022 China Collegiate Programming Contest (<strong>CCPC</strong>) (Shanghai region).
- *2021.07* <strong> Silver medal </strong> in National Olympiad in Informatics (<strong>NOI</strong>).
- *2021.03* <strong> Ranked 22nd nationwide </strong> in National Olympiad in Informatics (<strong>NOI</strong>) Online Senior Group.

