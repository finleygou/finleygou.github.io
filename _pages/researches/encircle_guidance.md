---
layout: default
permalink: /researches/encirclement-guidance/
title: "Coverage based encirclement interception method via deep reinforcement learning"
excerpt: "Coverage based encirclement interception method via deep reinforcement learning"
author_profile: true
---

# Coverage based encirclement interception method via deep reinforcement learning

## Background

When the target exhibits superior capabilities, a single agent struggles to gain an advantage in one-to-one engagement. Under this premise, deploying multiple weaker agents to cooperatively intercept the target becomes a better strategy. We therefore formulate the interception task as a multi-agent encirclement problem and train the team via multi-agent reinforcement learning, thereby raising the success rate against stronger target.

## Methods
1. We construct the agent-to-target Apollonius circle and forward-propagate the target’s reachable set over the upcoming horizon.

2. Encirclement positions are then optimized so that the union of Apollonius circles provides high-coverage of this forward reachable region.

3. A multi-agent reinforcement learning framework is designed to learn the cooperative interception policy, where each agent decides its action to maintain encirclement positions and intercept target.

## Visualization

The following figure demonstrate the agent-target Apollonius circle.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/encircle_guidance2025/encircle1.png' | relative_url }}" alt="fig1" />
    <figcaption>Agent-target Apollonius circle</figcaption>
  </figure>
</div>


The following figures demonstrate the training rewards under different scenarios.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/encircle_guidance2025/r_encirclement_4agts_circle.png' | relative_url }}" alt="fig1" />
    <figcaption> Reward 1</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/encircle_guidance2025/r_encirclement_5agts_sin.png' | relative_url }}" alt="fig2" />
    <figcaption> Reward 2</figcaption>
  </figure>
  
</div>

The following videos describe the encirclement interception process.

<div class="gif-pair">
  <figure>
    <img src="{{ '/assets/publication/encircle_guidance2025/info_encirclement_4agts_circle.gif' | relative_url }}" alt="fig1" />
    <figcaption> 4 agents interception</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/publication/encircle_guidance2025/info_encirclement_5agts_sin.gif' | relative_url }}" alt="fig2" />
    <figcaption> 5 agents interception</figcaption>
  </figure>

</div>

