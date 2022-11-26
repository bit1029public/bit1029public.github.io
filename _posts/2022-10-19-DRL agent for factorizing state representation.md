---
title: DRL agent for factorizing state representation
author: Hongyu Zang
layout: post
---
<!-- 日期可能需要改一下 -->
<div class="container">
	<p>In the cooperation of our lab, Mila, and MSR-Montreal, we designed a novel DRL framework to address the issue of designing the goal of the agent for high-dimensional sensory inputs by learning factorial representations of goals and processing the resulting representation via a discretization bottleneck.</p>
</div>
<div style="float:center;border:solid 1px 000;margin:20px;"><img src="/assets/images/research/img_reconstruct_vq.png"></div>
<div class="container">
	<p>We first test our method in Color-MNIST dataset to support the idea that we can learn factorized or compositional representationsin. Color-MNIST example to demonstrate factorized representations; reconstructing the original images with two factors. Leftmost: Original Image; Left-Middle: Reconstructed Image without substitution; Right-Middle: Reconstructed Image with one groups of discrete codes substituted by zero vectors; Rightmost: Reconstructed Image with the other groups of discrete codes substituted by zero vectors. Specifically, factor 1 tends to encode the shape of the digit, while factor 2 specialized in its color.</p>
</div>
<div style="float:center;border:solid 1px 000;margin:20px;"><img src="/assets/images/research/robot_reconstruct_vq.png"></div>
<div class="container">
	<p>We demonstrate the ability of DGRL to learn factorial representations on real world robot data, where the robot arm moves in presence of background video distractors. We show an autoencoder trained with 8 discrete codes to reconstruct images of a real-robotic arm with independently changing distractors (TV and lamp). The top two rows show the reconstruction of the initial images. In the bottom left two rows, we change one of the discrete factors to match its value in the first image, in the resulting reconstruction, the lamp has turned orange. On the bottom right two rows, we change another discrete factor, to match its value from the first image, and observe that it made the robotic arm point left.</p>
</div>