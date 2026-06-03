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

Hi, I'm Boyi Deng (邓博以), a PhD candidate at the University of Science and Technology of China (USTC), affiliated with the [Lab for Data Science](http://data-science.ustc.edu.cn/), under the supervision of [Prof. Fuli Feng](https://fulifeng.github.io/) and [Prof. Wenjie Wang](https://wenjiewwj.github.io/). My research interests include large language models and mechanistic interpretability, with a particular focus on how interpretability can be used to enhance practical model capabilities. (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=ADSff4oAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>)

# 🔥 News
- *2026.04*: &nbsp;🎉🎉 We released our new technical report, [Qwen-Scope: Turning Sparse Features into Development Tools for Large Language Models](https://arxiv.org/abs/2605.11887), which explores how sparse autoencoders can support practical workflows for analyzing, controlling, and improving LLMs.

# 💻 Internships
- *2024.08 - 2026.06*, Tongyi Lab, Alibaba Group, Hangzhou, China.
  - Supervised by [Dr. Basong Yang](https://scholar.google.com/citations?user=fXsHJXkAAAAJ) and [Dr. Yu Wan](https://scholar.google.com/citations?user=lGTsggUAAAAJ).

# 📄 Technical Reports
- [Qwen3 Technical Report](https://arxiv.org/abs/2505.09388), **Contributor**.
- [Qwen-Scope: Turning Sparse Features into Development Tools for Large Language Models](https://arxiv.org/abs/2605.11887), **First Author**. [Blog](https://qwen.ai/blog?id=qwen-scope) / [Hugging Face](https://huggingface.co/collections/Qwen/qwen-scope)

# 📝 Publications 
- `ACL 2025` [Unveiling Language-Specific Features in Large Language Models via Sparse Autoencoders](https://arxiv.org/abs/2505.05111), **Boyi Deng**, Yu Wan, Baosong Yang, Yidan Zhang, Fuli Feng.
- `ICLE 2026` [SASFT: Sparse Autoencoder-guided Supervised Finetuning to Mitigate Unexpected Code-Switching in LLMs](https://arxiv.org/abs/2507.14894), **Boyi Deng**, Yu Wan, Baosong Yang, Fei Huang, Wenjie Wang, Fuli Feng.
- `AAAI 2025` [CrAM: Credibility-Aware Attention Modification in LLMs for Combating Misinformation in RAG](https://arxiv.org/abs/2406.11497), **Boyi Deng**, Wenjie Wang, Fengbin Zhu, Qifan Wang, Fuli Feng.
- `EMNLP 2023` [Attack Prompt Generation for Red Teaming and Defending Large Language Models](https://aclanthology.org/2023.findings-emnlp.143/), **Boyi Deng**, Wenjie Wang, Fuli Feng, Yang Deng, Qifan Wang, Xiangnan He.
- `EMNLP 2025` [P-mmeval: A Parallel Multilingual Multitask Benchmark for Consistent Evaluation of LLMs](https://arxiv.org/abs/2411.09116), Yidan Zhang, Yu Wan, **Boyi Deng**, Baosong Yang, Hao-Ran Wei, Fei Huang, Bowen Yu, Dayiheng Liu, Junyang Lin, Jingren Zhou.
- `ACL 2026` [Controllable LLM Reasoning via Sparse Autoencoder-Based Steering](https://arxiv.org/abs/2601.03595), Yi Fang, Wenjie Wang, Mingfeng Xue, **Boyi Deng**, Fengli Xu, Dayiheng Liu, Fuli Feng.

# 📖 Educations
- *2023.09 - 2028.07 (Expected)*, PhD Candidate, University of Science and Technology of China (USTC).
- *2019.09 - 2023.07*, Bachelor, University of Science and Technology of China (USTC).
- *2016.09 - 2019.07*, Chengdu No. 7 High School.
