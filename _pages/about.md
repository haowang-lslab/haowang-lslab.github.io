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

Besides research, I've excelled in competitive programming, winning awards in OI, ICPC, CCPC and various other contests, under the guidance of <a href="https://apex.sjtu.edu.cn/members/yyu">Prof. Yong Yu</a>. See my <a href="assets/pdf/CV_Jizhou_Guo.pdf">CV</a> for details.

My research interests are primarily focused on Large Language Models and AI for Science. I'm always eager to engage in discussions about these topics, so please feel free to reach out if you'd like to chat!

<p style="text-align: center;">
<a href="mailto:sjtu18640985163@sjtu.edu.cn">Email</a> / 
<a href="https://scholar.google.com.hk/citations?user=fcBDdsYAAAAJ">Google Scholar</a> / 
<a href="https://github.com/Aster2024">Github</a> / 
<a href="https://www.linkedin.com/in/jizhou-guo-6971b6277">LinkedIn</a> / 
<a href="images/wechat.jpg">WeChat</a> /
<a href="images/qq.jpg">QQ</a> /
<a href="images/xiaohongshu.jpg">Xiaohongshu(RedNote)</a> /
<a href="assets/pdf/CV_Jizhou_Guo.pdf">CV</a>
</p>

# 🔥 News
- *2024.10*: &nbsp; Our work <a href="https://arxiv.org/abs/2410.10481">Llamdex</a> is on arXiv!
- *2024.09*: &nbsp; 🎉Our work <a href="https://arxiv.org/abs/2405.18711">Internal Consistency</a> is accepted to NeurIPS 2024! 🎉
- *2024.05*: &nbsp; Our work <a href="https://arxiv.org/abs/2405.18711">Internal Consistency</a> is on arXiv!

# 📝 Publications 
_<sup>*</sup> denotes equal contribution_

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/dp_knowledge_transfer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Model-Based Differentially Private Knowledge Transfer for Large Language Models**

Zhaomin Wu*, **Jizhou Guo**\*, Junyi Hou, Bingsheng He, Lixin Fan, Qiang Yang

_Under review_ 

<a href="https://arxiv.org/abs/2410.10481">[arXiv]</a>

- Proposed **Llamdex**, a novel framework that integrates privacy-preserving, domain-specific models into LLMs.
- Demonstrated significant performance gains in domain-specific tasks, **with up to 26% accuracy improvement** while maintaining differential privacy guarantees.
- Achieved comparable inference efficiency to base LLMs while enhancing domain-specific capabilities.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/internal_consistency.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Calibrating Reasoning in Language Models with Internal Consistency**

Zhihui Xie, **Jizhou Guo**, Tong Yu, Shuai Li

_NeurIPS 2024_

<a href="https://arxiv.org/abs/2405.18711">[arXiv]</a>

- Developed a novel "**internal consistency**" approach to calibrate reasoning in LLMs, **resulting in a significant boost in reasoning performance** without requiring additional training.
- Conducted in-depth analysis of Chain-of-Thought (CoT) reasoning in LLMs through the lens of internal representations. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/eeg.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**EEG-based Emotion Recognition in an Olfactory Stimulation Paradigm**

Jiaqi Wang, Zhengting Chen, Yifan Wu, Keyan Huang, Dian Zhang, **Jizhou Guo**, Xinglan Liu, Dan Peng, Weilong Zheng, Baoliang Lu

_Under review_

- Designed and executed experiments to predict human emotions from EEG signals under various olfactory stimuli.
- Implemented and compared multiple deep learning models (MLP, CNN, Transformer) with Domain-Adversarial Neural Networks (DANN).

</div>
</div>

<style>
.experience-box {
  display: flex;
  align-items: flex-start;
  margin-bottom: 20px;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  overflow: hidden;
}
.experience-image {
  width: 100px;
  min-width: 100px;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f5f5f5;
}
.experience-image img {
  max-width: 90%;
  max-height: 90%;
  object-fit: contain;
}
.experience-text {
  flex: 1;
  padding: 15px;
}
.experience-text h3 {
  margin-top: 0;
}
</style>

# 💼 Experience

<div class="experience-box">
  <div class="experience-image">
    <img src="images/nus_logo.jpeg" alt="NUS logo">
  </div>
  <div class="experience-text" markdown="1">

### National University of Singapore

2024.06 - 2024.08  
Research Assistant  
Advisor: [Prof. Bingsheng He](https://www.comp.nus.edu.sg/~hebs/)

  </div>
</div>

<div class="experience-box">
  <div class="experience-image">
    <img src="images/pku_logo.jpeg" alt="PKU logo">
  </div>
  <div class="experience-text" markdown="1">

### Peking University

2023.07  
Student Trainee  
Quantitative Biology Summer School of [Center for Life Sciences](http://www.cls.edu.cn/)

  </div>
</div>

<div class="experience-box">
  <div class="experience-image">
    <img src="images/tencent_logo.jpeg" alt="Tencent logo">
  </div>
  <div class="experience-text" markdown="1">

### Tencent Corporation

2022.08  
Research Intern  
[Spark Project (AI group)](https://mp.weixin.qq.com/s/V4aGR4unGb2tOhgurL4xmQ)

  </div>
</div>

<div class="experience-box">
  <div class="experience-image">
    <img src="images/sjtu_logo.jpeg" alt="SJTU logo">
  </div>
  <div class="experience-text" markdown="1">

### Shanghai Jiao Tong University

2022.09 - Present  
Bachelor of Science in Mathematics with Honors, Zhiyuan College  
Research Advisors:  
[Prof. Shuai Li](https://shuaili8.github.io/), [Prof. Bao-Liang Lu](https://bcmi.sjtu.edu.cn/~blu/), and [Prof. Wei-Long Zheng](https://weilongzheng.github.io/)

  </div>
</div>

I've also completed several course projects. See my [CV](assets/pdf/CV_Jizhou_Guo.pdf) for details.

[//]: # (- 2023.07: Student Trainee at Quantitative Biology Summer School of Center for Life Sciences, Peking University.)

[//]: # (- 2022.08: Research Intern at Tencent Spark Project of Tencent Corporation.)

[//]: # (- I've also completed several course projects. See my <a href="assets/pdf/CV_Jizhou_Guo.pdf">CV</a> for details.)


[//]: # (# 💻 Projects)

[//]: # ()
[//]: # (<div class='paper-box'><div class='paper-box-image'><div><img src='images/AD_bio.png' alt="sym" width="100%"></div></div>)

[//]: # (<div class='paper-box-text' markdown="1">)

[//]: # ()
[//]: # (Novel biological dressing for atopic dermatitis)

[//]: # ()
[//]: # (- Work done at Quantitative Biology Summer School of Center for Life Sciences, Peking University on 2023.07.)

[//]: # (- Conceptualized and simulated a novel bio-responsive bandage using MATLAB, modeling drug diffusion processes for optimized wound healing.)

[//]: # ()
[//]: # (</div>)

[//]: # (</div>)

[//]: # ()
[//]: # (<div class='paper-box'><div class='paper-box-image'><div><img src='images/spiderman.jpg' alt="sym" width="100%"></div></div>)

[//]: # (<div class='paper-box-text' markdown="1">)

[//]: # ()
[//]: # (Palm liveness detection)

[//]: # ()
[//]: # (- Work done at Tencent Spark Project of Tencent Corporation on 2022.08.)

[//]: # (- Engineered a robust palm liveness detection system.)

[//]: # ()
[//]: # (</div>)

[//]: # (</div>)

# 🎖 Honors and Awards
_Click <a href="assets/pdf/certificates.pdf">here</a> to view all certificates_
- *2025.01* <strong> Gold Award🥇 </strong> and <strong> First Runner-up </strong> in the National College Students' Career Planning Contest (Shanghai Region).
- *2024.12* Third-Class Academic Scholarship, SJTU (Top 20%).
- *2024.12* Zhiyuan Honors Scholarship.
- *2024.11* Zhiyuan <strong>First-Class</strong> Overseas Research Scholarship.
- *2024.09* Merit Student of SJTU.
- *2023.12* Second-Class Academic Scholarship, SJTU (Top 10%, ranked 2nd overall).
- *2023.12* Zhiyuan Honors Scholarship.
- *2023.12* Third Prize in Mathematics competition of Chinese College Students (Shanghai).
- *2023.09* <strong> First Prize </strong> in Shanghai Collegiate Programming Contest (Ranked 2nd in Shanghai).
- *2023.08* <strong> Gold Award🥇 </strong> in Astar Programming Contest (Shanghai Region) (Ranked 2nd in Shanghai).
- *2023.05* <strong> Gold Medal🥇 </strong> in 2023 China Collegiate Programming Contest (<strong>CCPC</strong>) National Invitational Contest (Hunan).  
- *2023.05* <strong> Gold Medal🥇 </strong> in 2023 International Collegiate Programming Contest (<strong>ICPC</strong>) Xi'an Invitational Contest.
- *2022.12* Zhiyuan Honors Scholarship.
- *2022.12* <strong> Gold Medal🥇 </strong> in 2022 International Collegiate Programming Contest (<strong>ICPC</strong>) Asia Hangzhou Regional Contest (Ranked 8th nationwide).
- *2022.09* <strong> Gold Medal🥇 </strong> in 2022 China Collegiate Programming Contest (<strong>CCPC</strong>) (Shanghai region).
- *2021.07* <strong> Silver Medal🥈 </strong> in National Olympiad in Informatics (<strong>NOI</strong>).
- *2021.03* <strong> Ranked 22nd nationwide </strong> in National Olympiad in Informatics (<strong>NOI</strong>) Online Senior Group.

# 🌈 Miscellaneous

Apart from academic studies and research, I have a wide range of interests, including piano and singing.

- I enjoy playing the piano🎹 and have passed <a href="https://www.abrsm.org/">ABRSM</a> Practical Grade 8 and <a href="https://www.ccmusic.edu.cn/">CCM</a> Amateur Grade 10, both the highest levels. I've also won awards in several piano competitions.
- I am passionate about singing🎤 and have passed <a href="https://www.ccmusic.edu.cn/">CCM</a> Amateur Grade 9 (highest level).
- I used to serve as the conductor of the choir in junior school.
- I also have some experience in public speaking🗣️ and won Gold Award🥇 in the National College Students' Career Planning Contest (Shanghai Region).
- I have participated in various algorithm competitions🖥️ and earned Gold Medals🥇 in ICPC/CCPC and a Silver Medal🥈 in NOI.
