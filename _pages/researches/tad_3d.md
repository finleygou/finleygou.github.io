---
layout: default
permalink: /researches/3D-TAD/
title: "Three-dimensional TAD game using deep reinforcement learning, 2025"
excerpt: "Three-dimensional TAD game using deep reinforcement learning"
author_profile: true
---

# Three-dimensional TAD game using deep reinforcement learning

## Background

This is the extended work of our paper in IROS 2025. In this work, we investigate a three-dimensional (3D) TAD game using hierarchical learning methods, with different entity positions, target maneuvers, and defender policies. The attacker policy is trained via DRL. To make the task difficult for attacker, the initial position is advantageous to defender and target.

## Methods
1. We designed the action space, state space, and reward function to the scenario. The action space is nonlinearly mapped to yield smoother control transients, while the reward aggregates two competing objectives: hitting target and evading defender.

2. A hierarchical reinforcement-learning paradigm is adopted: the attacker selects between two high-level options—evading the defender or hitting the target. All model parameters are updated via proximal policy optimization (PPO).

## Visualization

The following figure demonstrate the training reward using different algorithms.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/3D-TAD2025/rew-3D.png' | relative_url }}" alt="fig1" />
    <figcaption>Training reward</figcaption>
  </figure>
</div>


The following figures demonstrate the rendered trajectories for different scenarios.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/3D-TAD2025/0_trajectories_xyz.png' | relative_url }}" alt="fig1" />
    <figcaption> Trajectory 1</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/3D-TAD2025/01_trajectories_xyz.png' | relative_url }}" alt="fig2" />
    <figcaption> Trajectory 2</figcaption>
  </figure>

The following videos describe the 3D TAD game process under different target maneuvers.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/3D-TAD2025/circle.gif' | relative_url }}" alt="fig1" />
    <figcaption>Scenario 1: Circular target maneuver</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/3D-TAD2025/roller.gif' | relative_url }}" alt="fig2" />
    <figcaption>Scenario 2: Roller target maneuver</figcaption>
  </figure>

</div>

