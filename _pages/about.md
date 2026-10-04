---
layout: about
title: About
permalink: /
subtitle: <a href="mailto:xing-hao.chen@connect.polyu.hk">xing-hao.chen@connect.polyu.hk</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false

selected_papers: false
social: false

announcements:
  enabled: false
  scrollable: true
  limit: 7

latest_posts:
  enabled: false
  scrollable: false
  limit: 3
---

I am **Xinghao Chen**, a joint Ph.D. candidate in Computer Science at The Hong Kong Polytechnic University and Eastern Institute of Technology, Ningbo. I am fortunate to be advised by [Prof. Wenjie Li](https://polyunlp.github.io/home) and [Prof. Xiaoyu Shen](https://idt.eitech.edu.cn/nlp/#/). I received my B.S. in Intelligent Science and Technology from Nankai University in 2023. Since June 2026, I have been a research intern at Tencent Youtu Lab, working with [Dr. Junnan Dong](https://junnandong.github.io/) on position-independent KV cache reuse and latent memory for agents. For more details, please see my [CV](/assets/pdf/Xinghao_Chen_CV.pdf).

My research focuses on efficient reasoning and reusable context for large language models and agents, spanning KV cache reuse, latent memory, and reasoning compression. I have recently been focusing on the following directions:

- **Cross-Prefix Caching:** I study how to reuse independently cached skills, documents, and memories across changing prefixes without repeated prefill. Attuner ([[arXiv'26]](https://arxiv.org/abs/2609.36722)) learns query-side adaptation to read frozen KV caches, recovering near-full-prefill quality at near-PIC TTFT.
- **Latent-Space Reasoning:** latent reasoning landscape and taxonomy ([[EMNLP'26]](https://arxiv.org/abs/2505.16782)), effective supervision for latent chain-of-thought ([[ICML'26]](https://arxiv.org/abs/2606.20075)), memory disentanglement and query-conditioned latent graph reasoning ([[arXiv'26]](https://arxiv.org/abs/2609.18461)), continuous thought representations, etc.
- **Thought Compression & Distillation:** effective chain-of-thought distillation ([[ACL'25]](https://arxiv.org/abs/2502.18001)), condition-aware reasoning compression ([[EMNLP'26]](https://arxiv.org/abs/2606.21704)), reasoning efficiency, etc.
- **Applications (MLLMs):** visual layer selection for multimodal LLMs ([[EMNLP'25]](https://arxiv.org/abs/2504.21447)), visual token pruning ([[CVPR'26]](https://arxiv.org/abs/2602.23734)), etc.

## [News](/news/)

{% include news.liquid limit=true %}

## [Selected Publications](/publications/)

(\*) Equal Contribution. (†) Corresponding Author.

{% include selected_papers.liquid %}
