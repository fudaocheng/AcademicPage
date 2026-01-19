---
title: "The Agent's First Day: Benchmarking Learning, Exploration, and Scheduling in the Workplace Scenarios"
collection: publications
category: preprints
permalink: /publication/traineebench
# excerpt: 'This paper is about fixing template issue #693.'
date: 2026-01-13
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2601.08173'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

**Daocheng Fu\***, Jianbiao Mei\*, Rong Wu\*, Xuemeng Yang\*, Jia Xu, Ding Wang, Pinlong Cai, Yong Liu, Licheng Wen, Botian Shi

The rapid evolution of Multi-modal Large Language Models (MLLMs) has advanced workflow automation; however, existing research mainly targets performance upper bounds in static environments, overlooking robustness for stochastic real-world deployment. We identify three key challenges: dynamic task scheduling, active exploration under uncertainty, and continuous learning from experience. To bridge this gap, we introduce TraineeBench, a dynamic evaluation environment that simulates a "trainee" agent continuously exploring a novel setting. Unlike traditional benchmarks, TraineeBench evaluates agents along three dimensions: (1) context-aware scheduling for streaming tasks with varying priorities; (2) prudent information acquisition to reduce hallucination via active exploration; and (3) continuous evolution by distilling generalized strategies from rule-based, dynamically generated tasks. Experiments show that cutting-edge agents have significant deficiencies in dynamic environments, especially in active exploration and continual learning. Our work establishes a framework for assessing agent reliability, shifting evaluation from static tests to realistic, production-oriented scenarios. Our codes are available at [https://github.com/KnowledgeXLab/EvoEnv](https://github.com/KnowledgeXLab/EvoEnv)

More details at [here](https://arxiv.org/abs/2601.08173).