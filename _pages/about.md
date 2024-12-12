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

Hello! This is Yizhou Dang (党翌洲 in Chinese). I am currently a second-year PhD student at [Software College](http://sc.neu.edu.cn/) of [Northeastern University](http://www.neu.edu.cn/), Shenyang, China. 
I am fortunate to be advised by [Prof. Guibing Guo](https://guoguibing.github.io/cn/) at [DSLab](https://www.dslab.org.cn/). 
Before that, I earned my B.E. degree in 2023 at the same institute.
I am honored to work closely with [Dr. Enneng Yang](https://ennengyang.github.io/) and [Dr. Yuting Liu](https://scholar.google.com/citations?hl=zh-CN&user=lld-fdUAAAAJ).

My research interests focus on recommender systems (RS), especially sequential recommendation and data augmentation methods. 
Also, I am interested in large language models for RS.
Please feel free to contact me by email if you have any questions or seeking collaborations.


# 🔥 News

- *2024.12*: &nbsp;🎉 Three papers are accepted by AAAI 2025
- *2024.11*: &nbsp;🎉 One paper is accepted by TOIS
- *2024.09*: &nbsp;🔊 We released a survey on data augmentation for sequential recommendation
- *2024.07*: &nbsp;🎉 One paper is accepted by RecSys 2024
- *2023.10*: &nbsp;🎉 One paper is accepted by TKDE
- *2023.06*: &nbsp;🎓 I graduated from NEU!
- *2022.12*: &nbsp;🏅 I'm honored to receive the AAAI 2023 student scholarship
- *2022.11*: &nbsp;🎉 One paper is accepted by AAAI 2023


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

$^{\dagger}$ indicates corresponding author

## Surveys

- Data Augmentation for Sequential Recommendation: A Survey \
  `arXiv 2024` | [**Paper**](https://arxiv.org/abs/2409.13545) [**Code**](https://github.com/KingGugu/DA-CL-4Rec) <font color="red">450+ Papers!</font> [![](https://img.shields.io/github/stars/KingGugu/DA-CL-4Rec)](https://github.com/KingGugu/DA-CL-4Rec) \
  **Yizhou Dang**, Enneng Yang, Yuting Liu, Guibing Guo$^{\dagger}$, Linying Jiang, Xingwei Wang$^{\dagger}$, Jianzhe Zhao \
  The repository collects the latest research progress of Data Augmentation (DA) and Contrastive Learning (CL) in recommender systems. Comments and contributions are welcome.


## Research Papers

### In the year of 2025:

- Augmenting Sequential Recommendation with Balanced Relevance and Diversity \
  `AAAI 2025` | [**Paper**](https://arxiv.org/abs/2412.08300) [**Code**](https://github.com/KingGugu/BASRec) \
  **Yizhou Dang**, Jiahui Zhang, Yuting Liu, Enneng Yang, Yuliang Liang, Guibing Guo$^{\dagger}$, Jianzhe Zhao$^{\dagger}$, Xingwei Wang

- CoRA: Collaborative Information Perception by Large Language Model's Weights for Recommendation \
  `AAAI 2025` | [**Paper**](https://arxiv.org/abs/2408.10645) [**Code**](https://github.com/VanillaCreamer/CoRA) \
  Yuting Liu, Jinghao Zhang, **Yizhou Dang**, Yuliang Liang, Qiang Liu$^{\dagger}$, Guibing Guo$^{\dagger}$, Jianzhe Zhao, Xingwei Wang

- Multiple Purchase Chains with Negative Transfer Elimination for Multi-Behavior Recommendation \
  `AAAI 2025` | Just Accepted \
  Shuwei Gong, Yuting Liu, **Yizhou Dang**, Guibing Guo$^{\dagger}$, Jianzhe Zhao$^{\dagger}$, Xingwei Wang

### In the year of 2024:

- Efficient and Adaptive Recommendation Unlearning: A Guided Filtering Framework to Erase Outdated Preferences \
  `TOIS 2024` | [**Paper**](https://dl.acm.org/doi/10.1145/3706633) [**Code**](https://github.com/KingGugu/GFEraser) \
  **Yizhou Dang**, Yuting Liu, Enneng Yang, Guibing Guo$^{\dagger}$, Linying Jiang, Jianzhe Zhao, Xingwei Wang

- Repeated Padding for Sequential Recommendation \
  `RecSys 2024` <font color="red">Oral Presentation</font> | [**Paper**](https://arxiv.org/abs/2403.06372) [**Code**](https://github.com/KingGugu/RepPad) \
  **Yizhou Dang**, Yuting Liu, Enneng Yang, Guibing Guo, Linying Jiang, Xingwei Wang$^{\dagger}$, Jianzhe Zhao$^{\dagger}$

### In the year of 2023:

- TiCoSeRec: Augmenting Data to Uniform Sequences by Time Intervals for Effective Recommendation\
  `TKDE 2023` | [**Paper**](https://ieeexplore.ieee.org/abstract/document/10285049) [**Code**](https://github.com/KingGugu/TiCoSeRec) \
  **Yizhou Dang**, Enneng Yang, Guibing Guo$^{\dagger}$, Linying Jiang, Xingwei Wang$^{\dagger}$, Xiaoxiao Xu, Qinghui Sun, Hong Liu

- Uniform Sequence Better: Time Interval Aware Data Augmentation for Sequential Recommendation \
  `AAAI 2023` <font color="red">Oral Presentation</font> | [**Paper**](https://arxiv.org/abs/2212.08262) [**Code**](https://github.com/KingGugu/TiCoSeRec) [**Video**](https://doi.org/10.48448/wmh8-p908) [**中文解读**](https://zhuanlan.zhihu.com/p/592832740) \
  **Yizhou Dang**, Enneng Yang, Guibing Guo$^{\dagger}$, Linying Jiang, Xingwei Wang$^{\dagger}$, Xiaoxiao Xu, Qinghui Sun, Hong Liu


# 📖 Educations

- *2023.09 - 2028.06 (Expected)*, Ph.D. in Software Engineering, Northeastern University, Shenyang, China.
- *2019.09 - 2023.06*, Bachelor in Software Engineering, Northeastern University, Shenyang, China.


# 🏆 Honors and Awards

- *2023* National Scholarship for Graduate Student (Top 1%)
- *2022,2023* First-Class Scholarship from NEU
- *2022* AAAI Student Scholarship
- *2022* Baidu App User Experience Analysis Competition, First Prize
- *2022* Ministry of Education - Huawei Smart Base Future Stars
- *2021,2022* Huawei Smart Base Scholarship
- *2020* Outstanding Student of NEU


# 💻 Service

- Conference Reviewers: 
  - KDD 2024
- Journal Reviewers:
  - IEEE Transactions on Knowledge and Data Engineering (TKDE)
  - ACM Transactions on Recommender Systems (TORS)



[comment]: <> (# 💬 Invited Talks)

[comment]: <> (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[comment]: <> (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)

[comment]: <> (# 💻 Internships)

[comment]: <> (- *2019.05 - 2020.02*, [Lorem]&#40;https://github.com/&#41;, China.)