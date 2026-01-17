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

Hello! This is Yizhou Dang (党翌洲 in Chinese). I am currently a third-year Ph.D. student at [Software College](http://sc.neu.edu.cn/) of [Northeastern University](http://www.neu.edu.cn/), Shenyang, China. 
I am fortunate to be advised by [Prof. Guibing Guo](https://guoguibing.github.io/cn/). 
Before that, I earned my B.E. degree in 2023 at the same institute.
I am honored to work closely with [Dr. Enneng Yang](https://ennengyang.github.io/) and [Dr. Yuting Liu](https://vanillacreamer.github.io/).

My research interests focus on AI for science (protein representation learning and drug discovery) and recommender systems (sequential recommendation and LLM-based recommendation).

I am particularly interested in data-centric (data augmentation, data synthesis, etc) methods.

Please feel free to contact me by email if you have any questions or are seeking collaborations.

<ul class="projects-box" id="projects-box">
<li><em>2026.01</em>: 🎉 One paper is accepted by WWW 2026 </li>
<li><em>2025.12</em>: 🏅 I'm honored to Granted by the Youth Talents Support Project from China Association for Science and Technology (中国科协青年科技人才培育工程博士生专项计划)</li>
<li><em>2025.06</em>: 🎉 One paper is accepted by MIR</li>
<li><em>2025.04</em>: 🎉 Two papers are accepted by SIGIR 2025</li>
<li><em>2025.01</em>: 🎉 Two papers are accepted by DASFAA 2025</li>
<li><em>2024.12</em>: 🎉 One paper is accepted by ICASSP 2025</li>
<li><em>2024.12</em>: 🎉 Three papers are accepted by AAAI 2025</li>
<li><em>2024.11</em>: 🎉 One paper is accepted by TOIS</li>
<li><em>2024.09</em>: 🔊 We released a survey on data augmentation for sequential recommendation</li>
<li><em>2024.07</em>: 🎉 One paper is accepted by RecSys 2024</li>
<li><em>2023.10</em>: 🏅 I'm honored to receive the National Scholarship for graduate student (Top 1%)</li>
<li><em>2023.10</em>: 🎉 One paper is accepted by TKDE</li>
<li><em>2023.06</em>: 🎓 I graduated from NEU!</li>
<li><em>2022.12</em>: 🏅 I'm honored to receive the AAAI 2023 Student Scholarship</li>
<li><em>2022.11</em>: 🎉 One paper is accepted by AAAI 2023</li>
<p class="projects-show" id="projects-show"><span class="projects-show-text" id="projects-show-text">More</span></p>
</ul>


# 📝 Publications 

[comment]: <> (<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>)

[comment]: <> (<div class='paper-box-text' markdown="1">)

[comment]: <> ([Deep Residual Learning for Image Recognition]&#40;https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf&#41;)

[comment]: <> (**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun)

[comment]: <> ([**Project**]&#40;https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC&#41; <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>)

[comment]: <> (- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[comment]: <> (</div>)

[comment]: <> (</div>)

[comment]: <> (✨) 

$^{\dagger}$ indicates corresponding author, $^{\star}$ indicates equal contribution

## Surveys

- Data Augmentation for Sequential Recommendation: A Survey \
  `arXiv 2024` | [**Paper**](https://arxiv.org/abs/2409.13545) [**Code**](https://github.com/KingGugu/DA-CL-4Rec) [![](https://img.shields.io/github/stars/KingGugu/DA-CL-4Rec)](https://github.com/KingGugu/DA-CL-4Rec) <font color="red">700+ papers contained in the repository!</font>  \
  **Yizhou Dang**, Enneng Yang, Yuting Liu, Guibing Guo$^{\dagger}$, Linying Jiang, Xingwei Wang$^{\dagger}$, Jianzhe Zhao \
  The repository collects the latest research progress of Data Augmentation (DA) and Contrastive Learning (CL) in recommender systems. Comments and contributions are welcome.


## Research Papers

### In the year of 2026:

- Tail-Aware Data Augmentation for Long-Tail Sequential Recommendation \
  `WWW 2026` (In Press) | [**Paper**] [**Code**](https://github.com/KingGugu/TADA) \
  **Yizhou Dang**, Zhifu Wei, Minhan Huang, Lianbo Ma, Jianzhe Zhao, Guibing Guo, Xingwei Wang

### In the year of 2025:

- Data Augmentation as Free Lunch: Exploring the Test-Time Augmentation for Sequential Recommendation \
  `SIGIR 2025` <font color="red">Oral</font> | [**Paper**](https://arxiv.org/abs/2504.04843) [**Code**](https://github.com/KingGugu/TTA4SR) \
  **Yizhou Dang**, Yuting Liu, Enneng Yang, Minhan Huang, Guibing Guo$^{\dagger}$, Jianzhe Zhao$^{\dagger}$, Xingwei Wang

- Augmenting Sequential Recommendation with Balanced Relevance and Diversity \
  `AAAI 2025` <font color="red">Oral</font> | [**Paper**](https://arxiv.org/abs/2412.08300) [**Code**](https://github.com/KingGugu/BASRec) \
  **Yizhou Dang**, Jiahui Zhang, Yuting Liu, Enneng Yang, Yuliang Liang, Guibing Guo$^{\dagger}$, Jianzhe Zhao$^{\dagger}$, Xingwei Wang

- Beyond Single Sequence: User Correlation Guided Cross-Sequence Mixing for Sequential Recommendation \
  `MIR 2025` | Paper [**Code**](https://github.com/KingGugu/UCMRec) | Machine Intelligence Research \
  Jiahui Zhang$^{\star}$, **Yizhou Dang$^{\star}$**, Enneng Yang, Jianzhe Zhao, Linying Jiang, Guibing Guo$^{\dagger}$, Xingwei Wang

- Denoising Multi-Interest-Aware Logical Reasoning for Long-Sequence Recommendation \
  `SIGIR 2025` <font color="red">Oral</font> | [**Paper**](https://dl.acm.org/doi/10.1145/3726302.3729944) [**Code**](https://github.com/muzi1998/Denoising-Multi-Interest-Aware-Logical-Reasoning) \
  Fei Li, Qingyun Gao, **Yizhou Dang**, Enneng Yang, Guibing Guo$^{\dagger}$, Jianzhe Zhao, Xingwei Wang$^{\dagger}$

- CoRA: Collaborative Information Perception by Large Language Model's Weights for Recommendation \
  `AAAI 2025` <font color="red">Oral</font> | [**Paper**](https://arxiv.org/abs/2408.10645) [**Code**](https://github.com/VanillaCreamer/CoRA) \
  Yuting Liu, Jinghao Zhang, **Yizhou Dang**, Yuliang Liang, Qiang Liu$^{\dagger}$, Guibing Guo$^{\dagger}$, Jianzhe Zhao, Xingwei Wang

- Multiple Purchase Chains with Negative Transfer Elimination for Multi-Behavior Recommendation \
  `AAAI 2025` | [**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/33275) [**Code**](https://github.com/VanillaCreamer/MPC) \
  Shuwei Gong, Yuting Liu, **Yizhou Dang**, Guibing Guo$^{\dagger}$, Jianzhe Zhao$^{\dagger}$, Xingwei Wang

- Towards Unified Modeling for Positive and Negative Preferences in Sign-aware Recommendation \
  `DASFAA 2025` <font color="red">Oral</font> | [**Paper**](https://arxiv.org/abs/2403.08246) [**Code**](https://github.com/VanillaCreamer/LSGRec) \
  Yuting Liu, **Yizhou Dang**, Yuliang Liang, Qiang Liu, Guibing Guo$^{\dagger}$, Jianzhe Zhao, Xingwei Wang

- Self-supervised Hierarchical Representation for Medication Recommendation \
  `DASFAA 2025` <font color="red">Oral</font> | [**Paper**](https://arxiv.org/abs/2411.03143) [**Code**](https://github.com/yuliang-liang/HEIR) \
  Yuliang Liang, Yuting Liu, **Yizhou Dang**, Enneng Yang, Guibing Guo$^{\dagger}$, Wei Cai, Jianzhe Zhao, Xingwei Wang

- Harnessing Content and Structure in ID For Multimodal Recommendation \
  `ICASSP 2025` | [**Paper**](https://arxiv.org/pdf/2311.05956) [**Code**](https://github.com/VanillaCreamer/IDSF) \
  Yuting Liu$^{\star}$, Enneng Yang$^{\star}$, **Yizhou Dang**, Guibing Guo$^{\dagger}$, Qiang Liu, Yuliang Liang, Linying Jiang, Xingwei Wang


### In the year of 2024:

- Efficient and Adaptive Recommendation Unlearning: A Guided Filtering Framework to Erase Outdated Preferences \
  `TOIS 2024` | [**Paper**](https://dl.acm.org/doi/10.1145/3706633) [**Code**](https://github.com/KingGugu/GFEraser) | ACM Transactions on Information Systems \
  **Yizhou Dang**, Yuting Liu, Enneng Yang, Guibing Guo$^{\dagger}$, Linying Jiang, Jianzhe Zhao, Xingwei Wang

- Repeated Padding for Sequential Recommendation \
  `RecSys 2024` <font color="red">Oral</font> | [**Paper**](https://arxiv.org/abs/2403.06372v2) [**Code**](https://github.com/KingGugu/RepPad) \
  **Yizhou Dang**, Yuting Liu, Enneng Yang, Guibing Guo, Linying Jiang, Xingwei Wang$^{\dagger}$, Jianzhe Zhao$^{\dagger}$

### In the year of 2023:

- TiCoSeRec: Augmenting Data to Uniform Sequences by Time Intervals for Effective Recommendation\
  `TKDE 2023` | [**Paper**](https://ieeexplore.ieee.org/abstract/document/10285049) [**Code**](https://github.com/KingGugu/TiCoSeRec) | IEEE Transactions on Knowledge and Data Engineering \
  **Yizhou Dang**, Enneng Yang, Guibing Guo$^{\dagger}$, Linying Jiang, Xingwei Wang$^{\dagger}$, Xiaoxiao Xu, Qinghui Sun, Hong Liu

- Uniform Sequence Better: Time Interval Aware Data Augmentation for Sequential Recommendation \
  `AAAI 2023` <font color="red">Oral</font> | [**Paper**](https://arxiv.org/abs/2212.08262) [**Code**](https://github.com/KingGugu/TiCoSeRec) [**Video**](https://doi.org/10.48448/wmh8-p908) [**中文解读**](https://zhuanlan.zhihu.com/p/592832740) \
  **Yizhou Dang**, Enneng Yang, Guibing Guo$^{\dagger}$, Linying Jiang, Xingwei Wang$^{\dagger}$, Xiaoxiao Xu, Qinghui Sun, Hong Liu


# 📖 Educations

- *2023.09 - 2028.06 (Expected)*, Ph.D. in Software Engineering, Northeastern University, Shenyang, China.
- *2019.09 - 2023.06*, Bachelor in Software Engineering, Northeastern University, Shenyang, China.


# 🏆 Honors and Awards

- *2025* Youth Talents Support Project from China Association for Science and Technology \
&emsp;&emsp;&ensp;(中国科协青年科技人才培育工程博士生专项计划)
- *2023* National Scholarship for Graduate Student (Top 1%)
- *2022,2023* First-Class Scholarship from NEU
- *2022* AAAI Student Scholarship
- *2022* Baidu App User Experience Analysis Competition, First Prize
- *2022* Ministry of Education - Huawei Intelligent Foundation Future Stars
- *2021,2022* Huawei Intelligent Foundation Scholarship
- *2020* Outstanding Student of NEU


# 💻 Service

- Conference Reviewers: 
  - IJCAI 2025, 2026
  - AAAI 2026
  - KDD 2024
- Journal Reviewers:
  - IEEE Transactions on Knowledge and Data Engineering (TKDE)
  - ACM Transactions on Information Systems (TOIS)
  - ACM Transactions on Recommender Systems (TORS)


<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=343739&w=300&t=tt&d=eimuBYNRaOftpcjrQ9vfEm6Gggdhdu4Hf6ZB0_3CvPA&co=ffffff&cmo=009fff&cmn=18e0ff&ct=00196b'></script>


[comment]: <> (# 💬 Invited Talks)

[comment]: <> (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[comment]: <> (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)

[comment]: <> (# 💻 Internships)

[comment]: <> (- *2019.05 - 2020.02*, [Lorem]&#40;https://github.com/&#41;, China.)
