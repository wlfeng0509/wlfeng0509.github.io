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

<style>
  .rucred {
    display: inline-block;
    background-color: rgb(174, 11, 42);
    color: white;
    font-size: 0.8em;
    padding: 2px 6px;
    border-radius: 3px;
    margin-left: 8px;
    font-weight: bold;
    vertical-align: middle;
  }
  .badge {
    font-weight: 600;
    margin-bottom: 5px;
  }
</style>

<style>
  .logo-row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 2rem; 
  }
  .logo-row img {
    height: 60px;
    width: auto;
    /* 
       border-radius: 6px;
       box-shadow: 0 0 6px rgba(0,0,0,.15); */
  }
</style>

<style>
  .site-footer {
    text-align: center;
    font-size: 0.85em;
    color: rgb(128, 128, 128);
    margin: 2rem 0 1rem; 
  }
  .site-footer a {
    color: inherit;
    text-decoration: underline;
  }
</style>

<span class='anchor' id='about-me'></span>

Hi, I am Weilun Feng. I am currently a **master** student at [Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS)](https://www.ict.ac.cn/) (2024.9 -- now). I obtained my B.E. degree from Shen Yuan Honors College, Beihang University (2020.9 -- 2024.7).

My research interests focus on **efficient machine learning**. Specifically, I focus on deep model compression (e.g., binarization, quantization, and distillation), efficient generative models (e.g., efficient large language models and diffusion models). 


# 🔥 News
- *2025.07*: &nbsp;🎉 One paper about Traditional Chinese Medicinal Plant Dataset was accepted by **Scientific Data**.
- *2025.05*: &nbsp;🎉 One first-author paper and one co-author paper were accepted by **ICML 2025**.
- *2025.02*: &nbsp;🎉 One paper was accepted by **CVPR 2025**.
- *2025.01*: &nbsp;🎉 One first-author paper was accepted by **AAAI 2025** *(Oral)*.
- *2024.07*: &nbsp;🎉 One first-author paper was accepted by **ACM MM 2025** *(Oral)*.
- *2024.02*: &nbsp;🎉 One paper was accepted by **CVPR 2024**.

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Preprint</div><img src='../images/SeRe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[MPQ-DMv2: Flexible Residual Mixed Precision Quantization for Low-Bit Diffusion Models with Temporal Distillation](https://arxiv.org/abs/2507.04290)

**Weilun Feng**, Chuanguang Yang, Haotong Qin, Yuqi Li, Xiangqi Li, Zhulin An, Libo Huang, Boyu Diao, Fuzhen Zhuang, Michele Magno, Yongjun Xu, Yingli Tian, Tingwen Huang

- *Arxiv Preprint*

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Scientific Data</div><img src='../images/SeRe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[TCMP-300: A Comprehensive Traditional Chinese Medicinal Plant Dataset for Plant Recognition](https://www.nature.com/articles/s41597-025-05522-7)

Yanling Zhang, Wanhui Sun, Chuanguang Yang, Libo Huang, Zhulin An, **Weilun Feng**, Wenjing Tang, Yongjun Xu

- *Accepted at Scientific Data*

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='../images/SeRe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Q-VDiT: Towards Accurate Quantization and Distillation of Video-Generation Diffusion Transformers](https://arxiv.org/abs/2505.22167)

**Weilun Feng**, Chuanguang Yang, Haotong Qin, Xiangqi Li, Yu Wang, Zhulin An, Libo Huang, Boyu Diao, Zixiang Zhao, Yongjun Xu, Michele Magno

- *Accepted at Forty-second International Conference on Machine Learning (ICML, CCF-A) 2025* <span class="rucred">Poster</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='../images/SeRe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Geometric Feature Embedding for Effective 3D Few-Shot Class Incremental Learning](https://openreview.net/forum?id=CuASYs6XZW)

Xiangqi Li, Libo Huang, Zhulin An, **Weilun Feng**, Chuanguang Yang, Boyu Diao, Fei Wang, Yongjun Xu

- *Accepted at Forty-second International Conference on Machine Learning (ICML, CCF-A) 2025* <span class="rucred">Poster</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='../images/SeRe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Multi-party Collaborative Attention Control for Image Customization](https://arxiv.org/abs/2505.01428)

Han Yang, Chuanguang Yang, Qiuli Wang, Zhulin An, **Weilun Feng**, Libo Huang, Yongjun Xu

- *Accepted at Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR, CCF-A) 2025* <span class="rucred">Poster</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='../images/SeRe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[MPQ-DM: Mixed Precision Quantization for Extremely Low Bit Diffusion Models](https://arxiv.org/abs/2412.11549)

**Weilun Feng**, Haotong Qin, Chuanguang Yang, Zhulin An, Libo Huang, Boyu Diao, Fei Wang, Renshuai Tao, Yongjun Xu, Michele Magno

- *Accepted at Proceedings of the AAAI Conference on Artificial Intelligence (AAAI, CCF-A) 2025* <span class="rucred">Oral</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='../images/TICNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Relational Diffusion Distillation for Efficient Image Generation](https://arxiv.org/abs/2410.07679)

**Weilun Feng**, Chuanguang Yang, Zhulin An, Libo Huang, Boyu Diao, Fei Wang, Yongjun Xu

- *Accepted at Proceedings of the 32nd ACM international conference on multimedia (ACM MM, CCF-A) 2025* <span class="rucred">Oral</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='../images/TICNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reg-PTQ: Regression-specialized Post-training Quantization for Fully Quantized Object Detector](https://openaccess.thecvf.com/content/CVPR2024/html/Ding_Reg-PTQ_Regression-specialized_Post-training_Quantization_for_Fully_Quantized_Object_Detector_CVPR_2024_paper.html)

Yifu Ding, **Weilun Feng**, Chuyan Chen, Jinyang Guo, Xianglong Liu

- *Accepted at Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR, CCF-A) 2024* <span class="rucred">Poster</span>

</div>
</div>


# 🎖 Honors and Awards
- *2025.07*: &nbsp;💰 SIGKDD-supported KDD 2025 *Student Travel Award* – 1,000 USD
- *2025.06*: &nbsp;💰 *Presidential Scholarship* for Outstanding International Exchange – 40,000 CNY
- *2025.04*: &nbsp;💰 *Municipal Approval* for Student Innovation Project – 7,500 CNY
- *2025.01*: &nbsp;💰 Mitacs Globalink Internship Scholarship – 6,000 CAD
- *2024.12*: &nbsp;🏆 *National Second Prize*, 19th "Challenge Cup" National Undergraduate Curricular Academic Science and Technology Works
- *2024.10*: &nbsp;🏆 *Second Prize*, Beijing Mathematical Contest in Modeling
- *2024.10*: &nbsp;💰 *Second-class* Academic Scholarship – 3,000 CNY
- *2024.04*: &nbsp;💰 *Municipal Approval* for Student Innovation Project – 7,500 CNY
- *2024.04*: &nbsp;🎖 Outstanding Communist Youth League Member

# 📖 Educations
- *2025.01 – 2025.03*: &nbsp;🇺🇸 **Global Study Program, University of California, Davis**
  
  *- Major: Mathematics & Statistics, Graduated with Academic Perfection*

- *2022.09 – Present*: &nbsp;🇨🇳 **Gaoling School of Artificial Intelligence, Renmin University of China**
  
  *- Bachelor of Engineering in Artificial Intelligence, Supervisors: [Dr. Qi Qi](https://gsai.ruc.edu.cn/qiqi), [Dr. Xiao Zhang](https://pinkfloyd1989.github.io/Xiao_Zhang/)*


# 💻 Work Experiences
- *2025.07 – 2025.10*: &nbsp;🇨🇦 *Mitacs Globalink Research Intern & Visiting Research Student*, [Faculty of Computer Science](https://www.dal.ca/faculty/computerscience.html), Dalhousie University

  *- Lab: [Dalhousie Applied Machine Learning Research Lab](https://web.cs.dal.ca/~gaw/), Collaborator: [Dr. Ga Wu](https://wuga214.github.io/)*
  
  *- Project: AI safety for recommender systems in social media services*
  
- *2024.11 – Present*: &nbsp;🇨🇳 *Research Intern*, Beijing Key Laboratory of Research on Large Models and Intelligent Governance
- *2024.05 – 2024.09*: &nbsp;🇨🇳 *Research Intern*, Engineering Research Center of Next-Generation Intelligent Search and Recommendation, MOE


# 💼 Services
- Artifact badging reviewer, KDD 2025


# 🪽 Beyond Academics

I love **music, literature, travel and badminton**. I am a **campus singer** at Renmin University of China and have been invited to participate in various concerts and music festivals at RUC. I am also a **musician at NetEase Cloud Music**, and my stage name is [艾诺 Ayinor](http://music.163.com/#/artist?id=36180214). Recently, I am also working on my own new song, so stay tuned!


# 🌍 Visitor Map

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=1838a3&w=400&t=tt&d=opzTPaTNgNUrWvD_vjzXkFUMNo05ptM6XPnZfkpH53E&co=ffffff&cmo=af1616&cmn=1fba1f&ct=000000'></script>



<div class="logo-row">
  <img src="../images/ruc_logo.png"      alt="">
  <img src="../images/ucdavis_logo.png"  alt="">
  <img src="../images/dal_logo.png"      alt="">
  <img src="../images/mitacs_logo.png"      alt="">
</div>


<footer class="site-footer">
  <p>&copy; 2025 Zhiyuan Su. All rights reserved.</p>
  <p>
    Template adapted from
    <a href="https://github.com/RayeRen/acad-homepage.github.io"
       target="_blank" rel="noopener">Yi Ren</a>.
  </p>
</footer>
