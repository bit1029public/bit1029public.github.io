---
title: UVIN :An Universal DRL Method to Combine Planning and Learning
author: Li Zhang
layout: post
---
<div class="container">
	<p>Most existing DRL approaches focus on leveraging the deep neural network structure to approximate the value function via a trial-and-error learning process, but insufficiently address explicit planning computation as in the conventional model-based approaches. We proposed Universal Value Iteration Networks (UVIN) to combine model-free learning and model-based planning in common RL setting to improve long-term reasoning and inference.</p>
</div>
<div style="float:none;border:solid 1px 000;margin:20px;text-align:center"><img src="/assets/images/research/minecraft.gif"><br><em>Performance on Minecraft</em></div>
<div style="float:none;border:solid 1px 000;margin:20px;text-align:center"><img src="/assets/images/research/maze.png"><br>&nbsp;&nbsp;<em>Spatially-variant maze</em></div>
<div style="float:none;clear:both;"></div>
<div class="container">
	<p>Minecraft is a popular sandbox video game that allows players to explore, gather, and craft in a 3D world. To collect the desired items in the inventory, players need to plan whether to search for or synthesize a new item, and how. Thus, Minecraft is a typical problem requiring long-term reasoning. UVIN significantly outperforms other state-of-the-art approaches (GPPN, GVIN, VIN, Rainbow) in Minecraft and some variants of maze navigation we introduced. UVIN has been accepted as a conference paper by AAAI-2020 for oral presentation.</p>
</div>