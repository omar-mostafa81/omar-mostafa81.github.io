---
title: "WorldPlanner: Monte Carlo Tree Search and MPC with Action-Conditioned Visual World Models"
authors: "R. Khorrambakht, J. Ortiz-Haro, J. Amigo, <strong>O. Mostafa</strong>, D. Dugas, F. Meier, L. Righetti"
venue: ICRA 2026
year: 2025
arxiv: "https://arxiv.org/abs/2511.03077"
paper_url: "https://arxiv.org/abs/2511.03077"
tags:
  - World Models
  - MCTS
  - MPC
  - Robot Manipulation
abstract: >
  We present WorldPlanner, a framework that combines Monte Carlo Tree Search (MCTS) and Model Predictive Control (MPC)
  with action-conditioned visual world models for robot manipulation planning. In Stage 1, we train a visual world model
  from unstructured play data using a denoising objective. In Stage 2, MCTS plans trajectories using an action prior and
  the world model to simulate rollouts, guided by a trained reward model. In Stage 3, a local MPC controller executes
  the MCTS plan with a custom reward combining plan-following and action regularization. Accepted at ICRA 2026 and the
  World Modeling Workshop (Mila, Montreal).
images:
  - src: /assets/images/publications/worldplanner_mcts.jpg
    caption: "MCTS planning for the push-T task"
  - src: /assets/images/publications/worldplanner_mpc.jpg
    caption: "MPC execution on the Franka arm"
---

WorldPlanner addresses the challenge of long-horizon robot manipulation by decomposing the problem into three stages:
visual world model training, MCTS-based planning, and MPC execution. The key insight is to use action-conditioned
world models as a learned simulator within MCTS, enabling sample-efficient planning without ground-truth physics.

This work was conducted at the **Machines in Motion Laboratory, NYU Tandon**, under the supervision of
Prof. Ludovic Righetti and PhD student Rooholla Khorrambakht.
