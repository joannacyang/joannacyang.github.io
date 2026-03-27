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

I am currently a Ph.D. candidate at [The Hong Kong Polytechnic University (PolyU)](https://www.polyu.edu.hk/) under the supervision of [Prof. HUANG Xiao](https://www4.comp.polyu.edu.hk/~xiaohuang/index.html) with co-supervision by [Prof. CHUNG Fu Lai Korris](https://www.polyu.edu.hk/comp/people/academic-staff/prof-chung-fu-lai-korris/). I will be a visiting student at [Nanyang Technological University (NTU)](https://www.ntu.edu.sg/) under the supervision of [Prof. AN Bo](https://personal.ntu.edu.sg/boan/). Before that, I obtained my BEng from [Beihang University (BUAA)](https://www.buaa.edu.cn/) and MSc from [National University of Singapore (NUS)](https://nus.edu.sg/). My research interests include (Multi-Agent) Reinforcement Learning/ Decision Making, Large Language Models (LLMs), and AI in Fintech.

# 🎉 News
- [*2026.02*] Our survey on Graph-based Agent Memory is released. [[Paper](https://arxiv.org/abs/2602.05665)\|[Github](https://github.com/DEEP-PolyU/Awesome-GraphMemory)]
- [*2025.12*] I was awarded the competitive grant [ICRF](https://www.polyu.edu.hk/gs/current-students/polyu-phd-scholars-icrf/) (PolyU PhD Scholars International Collaborative Research Fellowship).
- [*2025.06*] I got the Best Poster Award in [ARSC'25](https://www.polyu.edu.hk/comp/news-and-events/news/2025/0625_rs-conference-2025/) (PolyU COMP - HKUST (GZ) INFH Research Student Conference).
- [*2025.04*] I passed the Ph.D. confirmation. Thanks to my supervisors and panel members [Prof. YIU Man Lung Ken](https://www.polyu.edu.hk/comp/people/academic-staff/prof-yiu-man-lung-ken/) and [Prof. LI Bo](https://www.polyu.edu.hk/comp/people/academic-staff/prof-li-bo/).


# 📔 Selected Publications ([Full List](https://scholar.google.com/citations?user=T72Zu6sAAAAJ&hl=zh-CN))
<span style="color: #000000">**[†]: Equal Contribution**</span>, <span style="color: #000000">**[‡]: Corresponding Author**</span>

## Preprint:
- **[arXiv]** Zhishang Xiang†, Chengyi Yang†, Zerui Chen, Zhimin Wei, Yunbo Tang, Zongpei Teng, Zexi Peng, Zongxia Li, Chengsong Huang, Yicheng He, **Chang Yang**, Xinrun Wang, Xiao Huang, Qinggang Zhang‡, Jinsong Su‡. [A Systematic Survey of Self-Evolving Agents: From Model-Centric to Environment-Driven Co-Evolution](https://www.techrxiv.org/users/1029728/articles/1389627-a-systematic-survey-of-self-evolving-agents-from-model-centric-to-environment-driven-co-evolution?commit=6f818df82a1e8f72c63c3cf6085aee6689e01db9).
- **[arXiv]** **Chang Yang†**, Chuang Zhou†, Yilin Xiao†, Su Dong, Luyao Zhuang, Yujing Zhang, Zhu Wang, Zijin Hong, Zheng Yuan, Zhishang Xiang, Shengyuan Chen‡, Huachi Zhou‡, Qinggang Zhang‡, Ninghao Liu, Jinsong Su, Xinrun Wang, Yi Chang, Xiao Huang. [Graph-based Agent Memory: Taxonomy, Techniques, and Applications](https://arxiv.org/abs/2602.05665).
- **[arXiv]** Junzhe Jiang†, **Chang Yang†**, Aixin Cui, Sihan Jin, Ruiyu Wang, Bo Li, Xiao Huang, Dongning Sun, Xinrun Wang‡. [FinMaster: A Holistic Benchmark for Mastering Full-Pipeline Financial Workflows with LLMs](https://arxiv.org/abs/2505.13533).
- **[arXiv]** Junzhe Jiang†, **Chang Yang†**, Xinrun Wang‡, Zhiming Li, Xiao Huang, Bo Li. [Resolving Latency and Inventory Risk in Market Making with Reinforcement Learning](https://arxiv.org/abs/2505.12465).
- **[arXiv]** Shuxin Li†, **Chang Yang†**, Youzhi Zhang, Pengdeng Li, Xinrun Wang‡, Xiao Huang, Hau Chan, Bo An. [In-Context Exploiter for Extensive-Form Games](https://arxiv.org/abs/2408.05575).


## Published:
- **[IJCNN'26]** Junzhe Jiang†, **Chang Yang†**, Xinrun Wang‡, Bo Li. [Beyond Regression: Binary Encoding Classification with Confidence for Stock Index Prediction](https://arxiv.org/abs/2506.03153).

- **[TMLR'26]** **Chang Yang**, Xinrun Wang‡, Junzhe Jiang, Qinggang Zhang, Xiao Huang. [LLM-Based World Models Can Make Decisions Solely, But Rigorous Evaluations are Needed](https://arxiv.org/abs/2411.08794).

- **[TMLR'26]** **Chang Yang†**, Ruiyu Wang†, Junzhe Jiang, Qi Jiang, Qinggang Zhang, Yanchen Deng, Shuxin Li, Shuyue Hu, Bo Li, Florian T. Pokorny, Xiao Huang, Xinrun Wang‡. [Nondeterministic Polynomial-time Problem Challenge: An Ever-Scaling Reasoning Benchmark for LLMs](https://openreview.net/pdf/8c1dbb4f91a485e1b8babc0477adffd7ad8c274b.pdf). [[Github](https://github.com/SMU-DIGA/nppc)\|[Leaderboard](https://ruiyuwang.github.io/nppc_leaderboard/)]
  
- **[AAAI'26]** Jiajun Cao, Qinggang Zhang‡, Yunbo Tang, Zhishang Xiang, **Chang Yang**, Jinsong Su‡. [Augmenting Intra-Modal Understanding in MLLMs for Robust Multimodal Keyphrase Generation](https://arxiv.org/pdf/2512.00928).  
<!--The 40th Annual AAAI Conference on Artificial Intelligence (AAAI'26)-->

- **[EMNLP'25]** **Chang Yang**, Xinrun Wang‡, Qinggang Zhang, Qi Jiang, Xiao Huang. [Efficient Integration of External Knowledge to LLM-based World Models via Retrieval-Augmented Generation and Reinforcement Learning](https://aclanthology.org/2025.findings-emnlp.504.pdf). (Findings)
<!--The 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP'25 Findings)-->

- **[ACL'25]** Huachi Zhou†, Jiahe Du†, Chuang Zhou, **Chang Yang**, Yilin Xiao, Yuxuan Xie, Xiao Huang‡. [Each Graph is a New Language: Graph Learning with LLMs](https://aclanthology.org/2025.findings-acl.902.pdf). (Findings)
<!--The 63rd Annual Meeting of the Association for Computational Linguistics (ACL'25 Findings)-->

- **[ICML'24]** Pengdeng Li, Shuxin Li†, **Chang Yang†**, Xinrun Wang‡, Shuyue Hu, Xiao Huang, Hau Chan, Bo An. [Configurable Mirror Descent: Towards a Unification of Decision Making](https://proceedings.mlr.press/v235/li24an.html).
<!--The 41st International Conference on Machine Learning (ICML'24)-->

- **[IJCAI'24]** Pengdeng Li, Shuxin Li†, **Chang Yang†**, Xinrun Wang‡, Xiao Huang, Hau Chan, Bo An. [Self-adaptive PSRO: Towards an Automatic Population-based Game Solver](https://www.ijcai.org/proceedings/2024/0016.pdf).
<!--The 33rd International Joint Conference on Artificial Intelligence (IJCAI'24)-->

- **[IJCAI'24]** Xinrun Wang†‡, **Chang Yang**†‡, Shuxin Li, Pengdeng Li, Xiao Huang, Hau Chan, Bo An. [Reinforcement Nash Equilibrium Solver](https://www.ijcai.org/Proceedings/2024/0030.pdf).  
<!--The 33rd International Joint Conference on Artificial Intelligence (IJCAI'24)-->


# 🏆 Honors and Awards
- [*2025*] PolyU Competitive [ICRF](https://www.polyu.edu.hk/gs/current-students/polyu-phd-scholars-icrf/) (~$55,000HKD) and [RSAP-Outgoing](https://www.polyu.edu.hk/gs/current-students/rsap_outgoing/) Grants
- [*2025*] PolyU [ARSC'25](https://www.polyu.edu.hk/comp/news-and-events/news/2025/0625_rs-conference-2025/) Best Poster Award
- [*2021*] BUAA Outstanding Graduate Award
<!--- [*2020*] MCM/ICM Honorable Mention-->
- [*2020*] BUAA First-class Scholarship in Academic Contest
- [*2018-2020*] BUAA First/Second-class Scholarship ~ Three Times

# 💼 Academic Service

- **Invited Reviewer:** ACL'26, ICLR'26, IJCAI('25,'26), IJCNN'26, AAMAS’24, TKDD’23
- **Teaching Assistant:** Database Systems (2023 Fall, 2025 Fall), Big Data Analytics (2024 Spring, 2024 Fall, 2025 Spring)

