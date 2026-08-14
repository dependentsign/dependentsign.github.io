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

Welcome to my personal homepage!

I am a second-year Ph.D. student in Computer Science at the [University of Illinois Chicago (UIC)](https://www.uic.edu/), advised by [Prof. Philip S. Yu](https://scholar.google.com/citations?user=D0lL1r0AAAAJ).
Before that, I received my M.S. degree in Artificial Intelligence from the [Institute of Automation, Chinese Academy of Sciences (CASIA)](http://english.ia.cas.cn/) in July 2024, where I was advised by [Prof. Qiang Liu](https://john-qiangliu.tech/), [Prof. Shu Wu](https://people.ucas.ac.cn/~shuwu?language=en) and [Prof. Liang Wang](http://www.cbsr.ia.ac.cn/users/liangwang/).

I have spent wonderful time at [BAAI](https://www.baai.ac.cn/english.html), and [NC State](https://dongkuanx27.github.io/page-lab.html) as a research intern/assistant.

# 🔍 Current Research Interests
My research develops evaluation methods and personalization systems for LLMs and AI agents, with an emphasis on understanding model behavior and building trustworthy, user-aligned systems. I currently focus on:
- **LLM & Agent Evaluation**: reliable multi-turn evaluation, user simulators, and benchmark design for real-world deployment.
- **Model Behavior & Trustworthy AI**: behavioral probes, robustness, explainability, and evaluation beyond self-report metrics.
- **Personalization & User Modeling**: long-term preferences, memory, user-intention reasoning, and adaptive interaction.

Representative work: **Core Sentiment Inventory (CSI)** for behavioral evaluation of LLM traits [[Paper]](https://openreview.net/forum?id=9J1wikUlHY) [[Code]](https://github.com/dependentsign/CSI).

I am open to **part-time AI research internships during the academic year** and **full-time research internships for Summer 2027**.


<div style="border-left: 4px solid #ccc; padding-left: 20px; margin: 20px 0; font-style: italic;">
  "With a Ph.D. you will have a better chance of spending the rest of your life doing what you want to do, instead of what someone else wants you to do."
  <div style="text-align: right; margin-top: 10px;">— William Lipscomb</div>
</div>

# 🔥 News
- *2026.06*: &nbsp;📢 Our survey, "Scaling LLM Agent Learning with Data Synthesis," is available as a preprint. [[Paper]](https://openreview.net/forum?id=pQYwkpYmLy)
- *2025.09*: &nbsp;📢 Release a novel personality traits evaluation tool, CSI, for assessing LLMs. [[GitHub]](https://github.com/dependentsign/CSI).
- *2024.07*: &nbsp;🎉🎉 A CIKM short paper has been accepted.
- *2024.05*: &nbsp;📢 Our paper "EX-FEVER: A Dataset for Multi-hop Explainable Fact Verification" has been accepted to ACL 2024 Findings!
- *2023.12*: &nbsp;🎉 Our paper "Interpretable Multimodal Out-of-Context Detection with Soft Logic Regularization" has been accepted as an oral presentation at ICASSP 2024!
- *2023.10*: &nbsp;🎉 Our paper "MenatQA: A New Dataset for Testing the Temporal Comprehension and Reasoning Abilities of Large Language Models" has been accepted to EMNLP 2023 Findings!


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/CSI.jpg' alt="CSI" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond BFI: The CSI for Enhanced Reliability and Validity in Evaluating LLM Personality Traits](https://openreview.net/forum?id=9J1wikUlHY)

**Huanhuan Ma**, Haisong Gong, Xiaoyuan Yi, Xing Xie, Philip S. Yu, Dongkuan Xu

**Preprint**, 2026

We propose **Core Sentiment Inventory (CSI)**, an implicit-association-test-inspired behavioral evaluation framework for more reliable assessment of LLM traits beyond self-report metrics.

[[Paper]](https://openreview.net/forum?id=9J1wikUlHY) [[Code]](https://github.com/dependentsign/CSI)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/500x300.png' alt="LLM agent data synthesis survey" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scaling LLM Agent Learning with Data Synthesis: A Comprehensive Survey](https://openreview.net/forum?id=pQYwkpYmLy)

Hanrong Zhang, Yankai Chen, Shicheng Fan, Dehai Min, Shaowen Chen, **Huanhuan Ma**, et al.

**Preprint**, 2026

We survey how task specifications, trajectories, feedback signals, and environments can be synthesized to support reliable and scalable learning for LLM agents.

[[Paper]](https://openreview.net/forum?id=pQYwkpYmLy)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/500x300.png' alt="Infinity-MM" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Infinity-MM: Scaling Multimodal Performance with Large-Scale and High-Quality Instruction Data](https://arxiv.org/abs/2410.18558)

Shuhao Gu, Jialing Zhang, et al., **Huanhuan Ma**, et al.

**arXiv preprint**, revised 2025

We introduce a large-scale, high-quality multimodal instruction dataset and a targeted synthetic-data pipeline for scaling vision-language models.

[[Paper]](https://arxiv.org/abs/2410.18558) [[Data]](https://huggingface.co/datasets/BAAI/Infinity-MM)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 Findings</div><img src='images/exfever.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EX-FEVER: A Dataset for Multi-hop Explainable Fact Verification](https://aclanthology.org/2024.findings-acl.556/)

**Huanhuan Ma**, Weizhi Xu, Yifan Wei, Liuji Chen, Liang Wang, Qiang Liu, Shu Wu, Liang Wang

**Findings of the Association for Computational Linguistics ACL 2024**


We introduce a large scale Multi-hop fact checking dataset with textual explanations, which can be used to evaluate the explainability of fact verification models.

[[PDF]](https://aclanthology.org/2024.findings-acl.556.pdf) [[Code]](https://github.com/dependentsign/EX-FEVER) [[Poster]](localfiles/acl_2024_poster.pdf) [[Slide]](localfiles/acl_2024_slide.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2024 Oral</div><img src='images/icassp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interpretable Multimodal Out-of-Context Detection with Soft Logic Regularization](https://ieeexplore.ieee.org/abstract/document/10447706/)

**Huanhuan Ma<sup>\*</sup>**, Jinghao Zhang<sup>\*</sup>, Qiang Liu, Shu Wu, Liang Wang

**IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2024**

We introduce a novel multimodal out-of-context detection framework with soft logic regularization, which can effectively detect out-of-context information with interpretability.

[[PDF]](localfiles/icassp2024.pdf) [[Slide]](localfiles/icassp_slide.pdf)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2024</div><img src='images/rake.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Does Knowledge Localization Hold True? Surprising Differences Between Entity and Relation Perspectives in Language Models](https://dl.acm.org/doi/10.1145/3627673.3679900)

Yifan Wei, Xiaoyan Yu, Yixuan Weng, **Huanhuan Ma**, Yuanzhe Zhang, Jun Zhao, Kang Liu

**Proceedings of the 33rd ACM International Conference on Information and Knowledge Management: CIKM 2024:**

This study investigates the differences between entity and relational knowledge through knowledge editing. Our findings reveal that entity and relational knowledge cannot be directly transferred or mapped to each other.

[[PDF]](https://arxiv.org/pdf/2409.00617) [[Code]](https://github.com/weiyifan1023/RaKE) 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023 Findings</div><img src='images/menatqa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MenatQA: A New Dataset for Testing the Temporal Comprehension and Reasoning Abilities of Large Language Models](https://aclanthology.org/2023.findings-emnlp.100/)

Yifan Wei, Yisong Su, **Huanhuan Ma**, Xiaoyan Yu, Fangyu Lei, Yuanzhe Zhang, Jun Zhao, Kang Liu

**Findings of the Association for Computational Linguistics: EMNLP 2023**

We construct Multiple Sensitive Factors Time QA (MenatQA), which encompasses three temporal factors (scope factor, order factor, counterfactual factor) with total 2,853 samples for evaluating the time comprehension and reasoning abilities of LLMs.

[[PDF]](https://aclanthology.org/2023.findings-emnlp.100.pdf) [[Code]](https://github.com/weiyifan1023/MenatQA) 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/rake.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Assessing knowledge editing in language models via relation perspective](https://arxiv.org/abs/2311.09053)

Yifan Wei, Xiaoyan Yu, **Huanhuan Ma**, Fangyu Lei, Yixuan Weng, Ran Song, Kang Liu

[[PDF]](https://arxiv.org/pdf/2311.09053) [[ArXiv]](https://arxiv.org/pdf/2311.09053) [[Code]](https://github.com/weiyifan1023/RaKE) 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DMBD 2022</div><img src='images/dmbd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-Cause Learning for Diagnosis Prediction](https://link.springer.com/chapter/10.1007/978-981-19-9297-1_23)

Liping Wang, Qiang Liu, **Huanhuan Ma**, Shu Wu, Liang Wang

Data Mining and Big Data (DMBD) 2022

<a href="localfiles/dmbd.pdf">[PDF] 

</div>
</div>


# 🚀 Projects

- [CSI: Core Sentiment Inventory](https://github.com/dependentsign/CSI): Behavioral evaluation toolkit for probing LLM traits beyond self-report.
- [EX-FEVER](https://github.com/dependentsign/EX-FEVER): Dataset and code for multi-hop explainable fact verification (ACL 2024 Findings).
- [Awesome-LLM-based-Evaluators](https://github.com/dependentsign/Awesome-LLM-based-Evaluators): A curated list of LLM-based evaluators for various NLP tasks. ![GitHub stars](https://img.shields.io/github/stars/dependentsign/Awesome-LLM-based-Evaluators?style=social)

# 📖 Educations
- *2025.08 - Present*, Ph.D. in Computer Science, University of Illinois Chicago (UIC). Advisor: Prof. Philip S. Yu.

- *2021.09 - 2024.07*, M.S. in Artificial Intelligence, Institute of Automation, Chinese Academy of Sciences. Advisors: Prof. Liang Wang and Prof. Qiang Liu.

- *2016.09 - 2020.07*, B.E. in Software Engineering, Zhengzhou University. 

# 💻 Internships

- *2024.07 - 2025.04*: Research Intern, [BAAI](https://www.baai.ac.cn/english.html), Beijing, China.
- *2023.12 - 2024.12*: Research Assistant, [NC State University, Generative Intelligent Computing (GIC) Lab](https://dongkuanx27.github.io/page-lab.html), NC, USA.

# 📅 Academic Services

## 📖 Reviewers
- International Conference on Learning Representations (ICLR), Reviewer (2025, 2026)
- Annual Meeting of the Association for Computational Linguistics (ACL), Reviewer (2026)
- AAAI 2026 Workshop (PerFM), Reviewer
- ACM International Conference on Information and Knowledge Management (CIKM), Program Committee Member (2024, 2025)
- Neural Information Processing Systems (NeurIPS), Reviewer (2023 Datasets & Benchmarks Track; 2026)
