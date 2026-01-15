---
title: "RE-Searcher: Robust Agentic Search with Goal-oriented Planning and Self-reflection"
collection: publications
category: preprints
permalink: /publication/RESearcher
# excerpt: 'This paper is about fixing template issue #693.'
date: 2025-09-30
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2509.26048'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

**Daocheng Fu\***, Jianbiao Mei*, Licheng Wen, Xuemeng Yang, Cheng Yang, Rong Wu, Tao Hu, Siqi Li, Yufan Shen, Xinyu Cai, Pinlong Cai, Botian Shi, Yong Liu, Yu Qiao

Large language models (LLMs) excel at knowledge-intensive question answering and reasoning, yet their real-world deployment remains constrained by knowledge cutoff, hallucination, and limited interaction modalities. Augmenting LLMs with external search tools helps alleviate these issues, but it also exposes agents to a complex search environment in which small, plausible variations in query formulation can steer reasoning into unproductive trajectories and amplify errors. We present a systematic analysis that quantifies how environmental complexity induces fragile search behaviors and, in turn, degrades overall performance. To address this challenge, we propose a simple yet effective approach to instantiate a search agent, RE-Searcher. During search, RE-Searcher explicitly articulates a concrete search goal and subsequently reflects on whether the retrieved evidence satisfies that goal. This combination of goal-oriented planning and self-reflection enables RE-Searcher to resist spurious cues in complex search environments and perform robust search. Extensive experiments show that our method improves search accuracy and achieves state-of-the-art results. Perturbation studies further demonstrate substantial resilience to noisy or misleading external signals, mitigating the fragility of the search process. We believe these findings offer practical guidance for integrating LLM-powered agents into more complex interactive environments and enabling more autonomous decision-making.

More details at [here](https://arxiv.org/abs/2509.26048).