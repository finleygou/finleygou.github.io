---
layout: default
permalink: /researches/coverage_detect/
title: "Cooperative detection of a mobile area using multiple directional sensors"
excerpt: "Cooperative detection of a mobile area using multiple directional sensors"
author_profile: true
---

# Cooperative detection of a mobile area using multiple directional sensors

## Background

Most coverage problems focus on optimizing the deployment of sensors to monitor a large area effectively. In this research, we address the challenge of detecting a small and mobile area using directional sensors with limited sensor range. The main difficulty lies in calculating the intersection part of multiple sectors and the target area, meanwhile efficiently planning the paths of multiple agents to maximize the detection probability.

## Methods
1. The relevant detection region is modeled as a convex set, the intersecting area is characterized via the inclusion–exclusion principle, and the associated objective function is formulated accordingly.

2. The sensing orientation for agents is treated as a decision variable, and the detection task is modeled as a constrained optimization problem whose objective is to maximize the probability integral over the intersection of the sensing sectors and the target area.

3. Model predictive control is employed to compute the sensor’s motion commands, minimizing energy expenditure while maintaining a prescribed coverage efficiency.

## Visualization

The following figures describe the coverage detection scenario in 2D situations. The time step shows the instant sensors orientations and the detected area.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/coverage2024/coverage.png' | relative_url }}" alt="fig1" />
    <figcaption>The illustration of detection task</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/coverage2024/Figure_1.png' | relative_url }}" alt="fig2" />
    <figcaption> Detected target true position</figcaption>
  </figure>

The following videos describe the coverage detection process in 2D and 3D situations. 3D experiment need further improvement.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/coverage2024/4v1_rhc.gif' | relative_url }}" alt="fig1" />
    <figcaption>The detection process in 2D</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/coverage2024/optimize.gif' | relative_url }}" alt="fig2" />
    <figcaption> The detection process in 3D</figcaption>
  </figure>

</div>

The following figure illustrate the coverage rate using traditional control method and model predictive control method.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/coverage2024/area.jpg' | relative_url }}" alt="fig1" />
    <figcaption>Coverage rate comparison</figcaption>
  </figure>
</div>