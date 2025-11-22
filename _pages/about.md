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

# 🎓 About Me

I am currently a Ph.D. candidate at [The Hong Kong Polytechnic University (PolyU)](https://www.polyu.edu.hk/) under the supervision of [Prof. HUANG Xiao](https://www4.comp.polyu.edu.hk/~xiaohuang/index.html) with co-supervision by [Prof. CHUNG Fu Lai Korris](https://www.polyu.edu.hk/comp/people/academic-staff/prof-chung-fu-lai-korris/). Before that, I obtained my BEng from [Beihang University (BUAA)](https://www.buaa.edu.cn/) and MSc from [National University of Singapore (NUS)](https://nus.edu.sg/). My research interests include (Multi-Agent) Reinforcement Learning/ Decision Making, Large Language Models (LLMs), and AI in Fintech.

# 🎉 News
- [*2025.11*] One paper is accepted by [AAAI'26](https://aaai.org/conference/aaai/aaai-26/).
- [*2025.08*] Our paper RAWM is accepted by EMNLP'25 (Findings). [[Paper](https://aclanthology.org/2025.findings-emnlp.504.pdf)\|[Github](https://github.com/joannacyang/rawm.git)]
- [*2025.06*] Got the Best Poster Award in [ARSC'25](https://www.polyu.edu.hk/comp/news-and-events/news/2025/0625_rs-conference-2025/) (PolyU COMP - HKUST (GZ) INFH Research Student Conference).
- [*2025.04*] I passed the Ph.D. confirmation. Thanks to my supervisors and panel members [Prof. YIU Man Lung Ken](https://www.polyu.edu.hk/comp/people/academic-staff/prof-yiu-man-lung-ken/), and [Prof. LI Bo](https://www.polyu.edu.hk/comp/people/academic-staff/prof-li-bo/).
- [*2025.04*] We released NPPC, an ever-scaling reasoning benchmark for LLMs. [[Paper](https://arxiv.org/abs/2504.11239)\|[Github](https://github.com/SMU-DIGA/nppc)]


# 📔 Selected Publications ([Full List](https://scholar.google.com/citations?user=T72Zu6sAAAAJ&hl=zh-CN))
<span style="color: #000000">**[†]: Equal Contribution**</span>, <span style="color: #000000">**[‡]: Corresponding Author**</span>

## Preprint:
- **[arXiv]** **Chang Yang†**, Ruiyu Wang†, Junzhe Jiang, Qi Jiang, Qinggang Zhang, Yanchen Deng, Shuxin Li, Shuyue Hu, Bo Li, Florian T Pokorny, Xiao Huang, Xinrun Wang‡. [Nondeterministic Polynomial-time Problem Challenge: An Ever-Scaling Reasoning Benchmark for LLMs](https://arxiv.org/abs/2504.11239).
- **[arXiv]** Junzhe Jiang†, **Chang Yang†**, Aixin Cui, Sihan Jin, Ruiyu Wang, Bo Li, Xiao Huang, Dongning Sun, Xinrun Wang‡. [FinMaster: A Holistic Benchmark for Mastering Full-Pipeline Financial Workflows with LLMs](https://arxiv.org/abs/2505.13533).
- **[arXiv]** Junzhe Jiang†, **Chang Yang†**, Xinrun Wang‡, Bo Li. [Why Regression? Binary Encoding Classification Brings Confidence to Stock Market Index Price Prediction](https://arxiv.org/abs/2506.03153).
- **[arXiv]** Junzhe Jiang†, **Chang Yang†**, Xinrun Wang‡, Zhiming Li, Xiao Huang, Bo Li. [Resolving Latency and Inventory Risk in Market Making with Reinforcement Learning](https://arxiv.org/abs/2505.12465).
- **[arXiv]** **Chang Yang**, Xinrun Wang‡, Junzhe Jiang, Qinggang Zhang, Xiao Huang. [Evaluating World Models with LLM for Decision Making](https://arxiv.org/abs/2411.08794).
- **[arXiv]** Shuxin Li†, **Chang Yang†**, Youzhi Zhang, Pengdeng Li, Xinrun Wang‡, Xiao Huang, Hau Chan, Bo An. [In-Context Exploiter for Extensive-Form Games](https://arxiv.org/abs/2408.05575).


## Published (First Author):
- **[EMNLP'25 Findings]** [Efficient Integration of External Knowledge to LLM-based World Models via Retrieval-Augmented Generation and Reinforcement Learning](https://aclanthology.org/2025.findings-emnlp.504.pdf)   <br>
**Chang Yang**, Xinrun Wang‡, Qinggang Zhang, Qi Jiang, Xiao Huang     <br>
The 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP'25 Findings)

- [Reinforcement Nash Equilibrium Solver](https://www.ijcai.org/Proceedings/2024/0030.pdf)     <br>
Xinrun Wang†‡, **Chang Yang†‡**, Shuxin Li, Pengdeng Li, Xiao Huang, Hau Chan, Bo An   <br>
The 33rd International Joint Conference on Artificial Intelligence (IJCAI'24)


## Published (Co-author):
- [Augmenting Intra-Modal Understanding in MLLMs for Robust Multimodal Keyphrase Generation](https://openreview.net/pdf?id=Z55FkgwUq7)  <br>
Jiajun Cao, Qinggang Zhang‡, Yunbo Tang, Zhishang Xiang, **Chang Yang**, Jinsong Su‡    <br>
The 40th Annual AAAI Conference on Artificial Intelligence (AAAI'26)

- [Each Graph is a New Language: Graph Learning with LLMs](https://aclanthology.org/2025.findings-acl.902.pdf)  <br>
Huachi Zhou†, Jiahe Du†, Chuang Zhou, **Chang Yang**, Yilin Xiao, Yuxuan Xie, Xiao Huang‡    <br>
The 63rd Annual Meeting of the Association for Computational Linguistics (ACL'25 Findings)

- [Configurable Mirror Descent: Towards a Unification of Decision Making](https://proceedings.mlr.press/v235/li24an.html)  <br>
Pengdeng Li, Shuxin Li†, **Chang Yang†**, Xinrun Wang‡, Shuyue Hu, Xiao Huang, Hau Chan, Bo An   <br>
The 41st International Conference on Machine Learning (ICML'24)

- [Self-adaptive PSRO: Towards an Automatic Population-based Game Solver](https://www.ijcai.org/proceedings/2024/0016.pdf)  <br>
Pengdeng Li, Shuxin Li†, **Chang Yang†**, Xinrun Wang‡, Xiao Huang, Hau Chan, Bo An    <br>
The 33rd International Joint Conference on Artificial Intelligence (IJCAI'24)


# 🏆 Honors and Awards
- [*2025*] PolyU ARSC 2025 Best Poster Award
- [*2021*] BUAA Outstanding Graduate Award
- [*2020*] MCM/ICM Honorable Mention
- [*2020*] BUAA First-class Scholarship in Academic Contest
- [*2018-2020*] BUAA First/Second-class Scholarship ~ Three Times

# 💼 Academic Service

- **Invited Reviewer:** ICLR'26, IJCAI’25, AAMAS’24, TKDD’23
- **Teaching Assistant:** Database Systems (2023 Fall, 2025 Fall), Big Data Analytics (2024 Spring, 2024 Fall, 2025 Spring)

