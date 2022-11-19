---
title: ADRQN :On Improving Deep Reinforcement Learning for POMDPs
author: Pengfei Zhu
layout: post
---
<div class="container">
	<p>Most of Deep Reinforcement Learning (DRL) methods focus on Markov Decision Process (MDP). Partially Observable Markov Decision Process (POMDP) is an extension of MDP. It naturally models planning tasks with uncertain action effects and partial state observability, however, finding an optimal policy is notoriously difficult. Inspired by belief state update based on Bayes’ theorem, we proposed Action-specific Deep Recurrent Q-Network (ADRQN) to improve DRL in POMDP.</p>
</div>
<div style="float:left;border:solid 1px 000;margin:20px;text-align:center"><img src="/assets/images/research/atari.gif"><br><em>Performance on Atari</em></div>
<div style="float:left;border:solid 1px 000;margin:20px;text-align:center"><img src="/assets/images/research/doom.gif"><br><em>Performance on Doom</em></div>
<div style="float:none;clear:both;"></div>
<div class="container">
	<p>Atari 2600 is a classical video game set and is used as benchmark tasks in many DRL research. We evaluated ADRQN in a flickering version of Atari, obscuring the entire screen with a certain probability at each time step. Further more, a 3D video game Doom is also used to evaluate our model. ADRQN achieves better performance than baseline methods (DQN, DRQN, DDRQN) in flickering Atari and Doom. ADRQN also appears to be the most competitive comparison approach among the follow-up works. The citations of ADRQN paper are up to 30 now.</p>
</div>