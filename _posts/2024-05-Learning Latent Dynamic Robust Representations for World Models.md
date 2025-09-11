---
title: Learning Latent Dynamic Robust Representations for World Models
author: Ruixiang Sun, Hongyu Zang
layout: post
---
<div class="container">
	<p>Visual Model-Based Reinforcement Learning (MBRL) promises to encapsulate agent's knowledge about the underlying dynamics of the environment, enabling learning a world model as a useful planner. However, top MBRL agents such as Dreamer often struggle with visual pixel-based inputs in the presence of exogenous or irrelevant noise in the observation space, due to failure to capture task-specific features while filtering out irrelevant spatio-temporal details.</p>
	<p>To tackle this problem, we apply a spatio-temporal masking strategy, a bisimulation principle, combined with latent reconstruction, to capture endogenous task-specific aspects of the environment for world models, effectively eliminating non-essential information. Joint training of representations, dynamics, and policy often leads to instabilities. To further address this issue, we develop a Hybrid Recurrent State-Space Model (HRSSM) structure, enhancing state representation robustness for effective policy learning. Our empirical evaluation demonstrates significant performance improvements over existing methods in a range of visually complex control tasks such as Maniskill with exogenous distractors from the Matterport environment.</p>
</div>
<div style="float:none;border:solid 1px 000;margin:18px;text-align:center"><img src="/assets/images/research/ICML_2024.png" width="60%"><br><em>Visualization of Multi-View Fusion</em></div>