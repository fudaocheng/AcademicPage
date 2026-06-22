---
title: "SymDrive: Realistic and Controllable Driving Simulator via Symmetric Auto-regressive Online Restoration"
collection: publications
category: manuscripts
permalink: /publication/SymDrive
# excerpt: 'This paper is about fixing template issue #693.'
date: 2025-12-25
venue: 'IROS 2026'
paperurl: 'https://arxiv.org/abs/2512.21618'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Zhiyuan Liu\*, **Daocheng Fu\***, Pinlong Cai, Lening Wang, Ying Liu, Yilong Ren, Botian Shi, Jianqiang Wang

High-fidelity and controllable 3D simulation is essential for addressing the long-tail data scarcity in Autonomous Driving (AD), yet existing methods struggle to simultaneously achieve photorealistic rendering and interactive traffic editing. Current approaches often falter in large-angle novel view synthesis and suffer from geometric or lighting artifacts during asset manipulation. To address these challenges, we propose SymDrive, a unified diffusion-based framework capable of joint high-quality rendering and scene editing. We introduce a Symmetric Auto-regressive Online Restoration paradigm, which constructs paired symmetric views to recover fine-grained details via a ground-truth-guided dual-view formulation and utilizes an auto-regressive strategy for consistent lateral view generation. Furthermore, we leverage this restoration capability to enable a training-free harmonization mechanism, treating vehicle insertion as context-aware inpainting to ensure seamless lighting and shadow consistency. Extensive experiments demonstrate that SymDrive achieves state-of-the-art performance in both novel-view enhancement and realistic 3D vehicle insertion.

More details at [here](https://arxiv.org/abs/2512.21618).
