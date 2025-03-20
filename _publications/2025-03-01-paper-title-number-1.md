---
title: "Spiking Variational Policy Gradient for Brain Inspired Reinforcement Learning"
collection: publications
category: manuscripts
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence (<strong>IEEE TPAMI</strong>), March 1'
authors: Zhile Yang, <strong>Shangqi Guo†</strong>, Ying Fang, Zhaofei Yu and Jian K. Liu
excerpt: <strong>Summary:</strong> We design a recurrent winner-take-all network and propose the spiking variational policy gradient (SVPG), a new R-STDP learning method derived theoretically from the global policy gradient.
date: 2025-03-01
codeurl: https://github.com/yzlc080733/SVPG2023
paperurl: https://ieeexplore.ieee.org/abstract/document/10786920
---
<strong>Abstract:</strong> Recent studies in reinforcement learning have explored brain-inspired function approximators and learning algorithms to simulate brain intelligence and adapt to neuromorphic hardware. Among these approaches, reward-modulated spike-timing-dependent plasticity (R-STDP) is biologically plausible and energy-efficient, but suffers from a gap between its local learning rules and the global learning objectives, which limits its performance and applicability. In this paper, we design a recurrent winner-take-all network and propose the spiking variational policy gradient (SVPG), a new R-STDP learning method derived theoretically from the global policy gradient. Specifically, the policy inference is derived from an energy-based policy function using mean-field inference, and the policy optimization is based on a last-step approximation of the global policy gradient. These fill the gap between the local learning rules and the global target. In experiments including a challenging ViZDoom vision-based navigation task and two realistic robot control tasks, SVPG successfully solves all the tasks. In addition, SVPG exhibits better inherent robustness to various kinds of input, network parameters, and environmental perturbations than compared methods.

<strong>Citation:</strong> Z. Yang, S. Guo, Y. Fang, Z. Yu and J. K. Liu, "Spiking Variational Policy Gradient for Brain Inspired Reinforcement Learning," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 47, no. 3, pp. 1975-1990, March 2025, doi: 10.1109/TPAMI.2024.3511936. 

