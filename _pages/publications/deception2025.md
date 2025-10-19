---
layout: default
permalink: /publications/deception2025/
title: "Modeling Deception in Multi-Robot Target-Attacker-Defender Game via Deep Reinforcement Learning (IROS 2025)"
excerpt: "Modeling Deception in Multi-Robot Target-Attacker-Defender Game via Deep Reinforcement Learning — IROS 2025"
author_profile: true
---

# Modeling Deception in Multi-Robot Target-Attacker-Defender Game via Deep Reinforcement Learning

## Abstract
Deception is a crucial strategy in adversarial scenarios,
yet its application in multi-agent confrontations remains
understudied. This paper investigates deception in a **multi-robot
Target-Attacker-Defender (MR-TAD)** game, where Attackers
aim to capture Targets while evading Defenders. To model
deception effectively, we propose a **hierarchical decision-making**
framework that integrates multi-agent reinforcement learning
(MARL) for **high-level deceptive strategies** and optimal control
for **low-level motion control**. Furthermore, we introduce a novel
composite deception-oriented reward function, which combines
hitting rewards, belief switch rewards, and position advantage
rewards to facilitate the training of deceptive behaviors. Simulation
results across varying numbers of robots demonstrate
that incorporating deception significantly increases the success
rate of Attackers, with an average improvement of over 70%
compared to non-deceptive strategies. Additionally, real-world
experiments with omnidirectional mobile robots further confirm
the effectiveness of the proposed method. This study establishes
a generalizable framework for modeling deception in multiagent
systems, with potential applications in various multi-agent
scenarios.

## Contributions
1. We formulated a problem of MR-TAD games where
agents can switch their goals, and a novel hierarchical
decision-making scheme is proposed to model deception
in MR-TAD games.
2. A composite deception-oriented reward design method
is presented to facilitate the training of deceptive
behaviors, greatly improving training efficiency and
convergence.
3. Simulations of varying numbers of robots are carried
out to demonstrate the scalability and robustness of our
method. Besides, we conducted real-world experiments
based on omnidirectional vehicles.

## Visualization

The following figures describe the overall structure of this work, and the illustration of **Target-Attacker-Defender** game. Use T, A, and D to denote Target, Attacker, and Defender, respectively.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/deception2025/structure.png' | relative_url }}" alt="deception gif 1" />
    <figcaption>Overall structure of the MR-TAD game</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/deception2025/TAD_scenario.png' | relative_url }}" alt="deception gif 2" />
    <figcaption> Illustration of sub-TAD scenario </figcaption>
  </figure>

</div>

The following figures illustrate the training reward and the belief switch process in 6T-3A-4D scenario.
<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/deception2025/reward_6t3a4d.png' | relative_url }}" alt="deception gif 3" />
    <figcaption>Training reward curve</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/deception2025/belief_6t3a4d.png' | relative_url }}" alt="deception gif 4" />
    <figcaption>Belief switch process of Attackers</figcaption>
  </figure>


The following GIFs illustrate the deception process of multiple Attacker robots trained using our proposed method, and a comparative experiment that use no deception under the same setting.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/deception2025/2t1a1d.gif' | relative_url }}" alt="deception gif 5" />
    <figcaption>2T-1A-1D game with deception</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/deception2025/2t1a1d_unsuc.gif' | relative_url }}" alt="deception gif 6" />
    <figcaption>2T-1A-1D game without deception</figcaption>
  </figure>

</div>

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/deception2025/3t2a2d.gif' | relative_url }}" alt="deception gif 7" />
    <figcaption>3T-2A-2D game with deception</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/deception2025/3t2a2d_unsuc.gif' | relative_url }}" alt="deception gif 8" />
    <figcaption>3T-2A-2D game without deception</figcaption>
  </figure>

</div>

<!-- 4t2a3d -->
<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/deception2025/4t2a3d.gif' | relative_url }}" alt="deception gif 9" />
    <figcaption>4T-2A-3D game with deception</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/deception2025/4t2a3d_unsuc.gif' | relative_url }}" alt="deception gif 10" />
    <figcaption>4T-2A-3D game without deception</figcaption>
  </figure>

<!-- 6t3a4d -->
</div>
<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/deception2025/6t3a4d.gif' | relative_url }}" alt="deception gif 11" />
    <figcaption>6T-3A-4D game with deception</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/deception2025/6t3a4d_unsuc.gif' | relative_url }}" alt="deception gif 12" />
    <figcaption>6T-3A-4D game without deception</figcaption>
  </figure>

</div>