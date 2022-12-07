---
title: Inverse Reinforcement Learning
author: Jie Huang
layout: post
---
<div class="container">
	<p>Inverse Reinforcement Learning (IRL) is mainly for complex tasks where the reward function is difficult to formulate. In general, IRL is to learn the reward function from the expert demonstrations, which can be understood as explaining the expert policy with the reward function we learned. When learning policies based on optimal sequence samples is needed, we can combine inverse reinforcement learning and deep learning to improve the accuracy of the reward function and the effect of the policy.</p>
	<p>Our work aims to utilize the inverse reinforcement learning algorithm or the imitation learning algorithm to solve related complex tasks, and apply the policy learned from the simulation environment to the robotics. The robot/agent is expected to learn from the training set demonstrated by the experts and achieves/exceeds the expert performance.</p>
</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="/assets/images/research/dogbot.jpg" width="264"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/assets/images/research/dogbot2.png" width="258">
<tr>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   &nbsp;&nbsp;&nbsp;
   <td align="center">Robot Dog</td>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   <td align="center">Simulation environment</td>
</tr>