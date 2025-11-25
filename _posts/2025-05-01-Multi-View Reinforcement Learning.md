---
title: Multi-View Reinforcement Learning
author: Zeyu Wang, Yao-Hui Li
layout: post
---
<div class="container">
	<p>In this study, we designed a novel Multi-View Reinforcement Learning (MVRL) framework, Multi-view Fusion State for Control (MFSC), to address the challenge of learning compact and task-relevant representations from multi-view observations, particularly when facing redundancy, distractors, or missing views. This is achieved by firstly incorporating bisimulation metric learning into the MVRL pipeline, and secondly introducing a multiview-based mask and latent reconstruction auxiliary task to effectively exploit shared information and significantly improve the agent's robustness to missing observations.</p>
</div>
<div style="float:none;border:solid 1px 000;margin:20px;text-align: center;"><img src="/assets/images/research/img_reconstruct_vq.png"></div>
<div class="container">
	<p>MVRL provides agents with multi-view observations to perceive environments more effectively. The goal is to extract compact and task-relevant latent representations from these views for use in control tasks. However, this is challenging due to redundant or distracting information and missing views.</p>
</div>
<div style="float:none;border:solid 1px 000;margin:20px;text-align: center;"><img src="/assets/images/research/MFSC_vis.png" style="width: 70%;"></div>
<div class="container">
	<p>Our work introduces Multi-view Fusion State for Control (MFSC), a method that uniquely integrates bisimulation metric learning into MVRL to learn better task-relevant representations. We also propose a multi-view-based mask and latent reconstruction auxiliary task that leverages shared information across views and enhances robustness to missing data.</p>
</div>