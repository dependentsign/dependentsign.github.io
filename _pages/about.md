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

Welcome to Huanhuan Ma (Andy)'s Personal Homepage!

I am a master student at the [Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn/) (expected to graduate in June 2024). Additionally, I am a member at the [Center for Research on Intelligent Perception and Computing (CRIPAC)](http://cripac.ia.ac.cn/en/EN/volumn/home.shtml), National Laboratory of Pattern Recognition (NLPR). I am fortunate to be advised by [Qiang Liu](https://john-qiangliu.tech/) and [Liang Wang](http://www.cbsr.ia.ac.cn/users/liangwang/).

My research interests lie in the field of natural language processing (NLP), with a focus on fake information detection, including fact verification and out-of-context detection. Currently, I am highly intrigued by exploring the intersection of Large Language Models (LLMs) and AI safety.

I have spent wonderful time at [BAAI](https://www.baai.ac.cn/english.html), and [NC State](https://dongkuanx27.github.io/page-lab.html) as a research intern/assistant.

<div style="border-left: 4px solid #ccc; padding-left: 20px; margin: 20px 0; font-style: italic;">
  "With a Ph.D. you will have a better chance of spending the rest of your life doing what you want to do, instead of what someone else wants you to do."
  <div style="text-align: right; margin-top: 10px;">— William Lipscomb</div>
</div>

# 🔥 News
- *2024.07*: &nbsp;🎉🎉 A CIKM short paper has been accepted. Congratulations to [YiFan Wei](https://github.com/weiyifan1023)🎉.
- *2024.05*: &nbsp;📢 Our paper "EX-FEVER: A Dataset for Multi-hop Explainable Fact Verification" has been accepted to ACL 2024 Findings!
- *2023.12*: &nbsp;🎉 Our paper "Interpretable Multimodal Out-of-Context Detection with Soft Logic Regularization" has been accepted as an oral presentation at ICASSP 2024!
- *2023.10*: &nbsp;🎉 Our paper "MenatQA: A New Dataset for Testing the Temporal Comprehension and Reasoning Abilities of Large Language Models" has been accepted to EMNLP 2023 Findings!


# 📝 Publications 

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

- [Awesome-LLM-based-Evaluators](https://github.com/dependentsign/Awesome-LLM-based-Evaluators): A curated list of LLM-based evaluators for various NLP tasks. ![GitHub stars](https://img.shields.io/github/stars/dependentsign/Awesome-LLM-based-Evaluators?style=social)

# 📖 Educations
- *2021.09 - 2024.07*, M.S. in Artificial Intelligence, Institute of Automation, Chinese Academy of Sciences. Advisors: Prof. Liang Wang and Prof. Qiang Liu.

- *2016.09 - 2020.07*, B.E. in Software Engineering, Zhengzhou University. 

# 💻 Internships

- *2024.07 - Present*: Research Intern, [BAAI](https://www.baai.ac.cn/english.html), Beijing, China.
- *2023.12 - Present*: Research Assistant, [NC State University, Generative Intelligent Computing (GIC) Lab](https://dongkuanx27.github.io/page-lab.html), NC, USA.

# 📅 Academic Services

## 📖 Reviewers
- Annual Conference on Neural Information Processing Systems (NeurIPS) Dataset&Benchmark track 2023, Reviewer
- ACM International Conference on Information and Knowledge Management (CIKM) 2024, PC member