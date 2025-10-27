---
layout: default
permalink: /researches/coverage_circle/
title: "Coordinated Swarm Interception Method Based on Area Coverage and Adaptive Dynamic Programming"
excerpt: "Coordinated Swarm Interception Method Based on Area Coverage and Adaptive Dynamic Programming"
author_profile: true
---

# Coordinated Swarm Interception Method Based on Area Coverage and Adaptive Dynamic Programming

## Background
<!-- a moving target swarm, we first assign target points,  -->
This research addresses the issue of low cost-effectiveness in intercepting swarm targets for multi-agent systems. We designed a cooperative interception algorithm based on regional coverage and adaptive dynamic programming. 

## Methods
1. A maneuver library consisting four types of cluster target behaviors is constructed, taking into account the morphological changes and motion trajectories of target clusters. The communication constraints of UAV clusters during actual flight are characterized using connectivity maintenance methods.

2. A distributed gradient descent method is employed to solve for optimal interception points to maximize strike probability, and two greedy initial point generation strategies are designed to enhance the quality of initial interception points and strike effectiveness. 

3.  Additionally, to address various uncertainties in the environment, a robust adaptive optimal interception guidance based on differential games is realized using adaptive dynamic programming methods.

- My contribution: part 1 and 2.

## Visualization

The following figures describe the initial coverage conditions and heat map of coverage density.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/coverage2023/cover1.png' | relative_url }}" alt="fig1" />
    <figcaption>The heat map of coverage density</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/coverage2023/cover2.png' | relative_url }}" alt="fig2" />
    <figcaption> Initial position of assigned coverage points </figcaption>
  </figure>

</div>

The following figures illustrate the adaptive adjustment process of interception points under different swarm maneuvers.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/coverage2023/expand.gif' | relative_url }}" alt="gif 1" />
    <figcaption> Expand maneuver </figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/coverage2023/shrink.gif' | relative_url }}" alt="deception gif 4" />
    <figcaption>Shrink maneuver</figcaption>
  </figure>


The cooperative guidance process of multiple interceptors.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/coverage2023/circle+optimal.gif' | relative_url }}" alt="gif 3" />
    <figcaption>Scenario 1</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/coverage2023/targetadd+optimal.gif' | relative_url }}" alt="gif 4" />
    <figcaption>New targets added</figcaption>
  </figure>

</div>