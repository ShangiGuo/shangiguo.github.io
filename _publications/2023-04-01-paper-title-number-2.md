---
title: "Adjacency Constraint for Efficient Hierarchical Reinforcement Learning"
collection: publications
category: manuscripts
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence (<strong>IEEE TPAMI</strong>), April 01'
authors: Tianren Zhang*, <strong>Shangqi Guo*†</strong>, Tian Tan, Xiaolin Hu and Feng Chen†
excerpt: <strong>Summary:</strong> We proposes an adjacency constraint for goal-conditioned hierarchical reinforcement learning that restricts high-level actions to a k-step adjacent region, theoretically preserving optimality in deterministic MDPs and improving training efficiency in stochastic MDPs, leading to significant performance gains in simulated robotics tasks.
date: 2023-04-01
codeurl: https://github.com/trzhang0116/HRAC
paperurl: https://ieeexplore.ieee.org/abstract/document/9833270
---
<strong>Abstract:</strong> Goal-conditioned Hierarchical Reinforcement Learning (HRL) is a promising approach for scaling up reinforcement learning (RL) techniques. However, it often suffers from training inefficiency as the action space of the high-level, i.e., the goal space, is large. Searching in a large goal space poses difficulty for both high-level subgoal generation and low-level policy learning. In this article, we show that this problem can be effectively alleviated by restricting the high-level action space from the whole goal space to a k-step adjacent region of the current state using an adjacency constraint. We theoretically prove that in a deterministic Markov Decision Process (MDP), the proposed adjacency constraint preserves the optimal hierarchical policy, while in a stochastic MDP the adjacency constraint induces a bounded state-value suboptimality determined by the MDP's transition structure. We further show that this constraint can be practically implemented by training an adjacency network that can discriminate between adjacent and non-adjacent subgoals. Experimental results on discrete and continuous control tasks including challenging simulated robot locomotion and manipulation tasks show that incorporating the adjacency constraint significantly boosts the performance of state-of-the-art goal-conditioned HRL approaches.

<strong>Citation:</strong> T. Zhang, S. Guo, T. Tan, X. Hu and F. Chen, "Adjacency Constraint for Efficient Hierarchical Reinforcement Learning," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 45, no. 4, pp. 4152-4166, 1 April 2023, doi: 10.1109/TPAMI.2022.3192418. 
