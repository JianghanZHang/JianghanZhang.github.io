---
layout: page
title: Predicting 3D Action Target from 2D Egocentric Vision for HRI
description: Improved safety and efficiency in Human Robot Interaction (HRI) with a 3D human action target prediction algorithm from 2D egocentric vision, implemented real-world HRI demonstrations on a UR10e robot. (paper accepted by ICRA 2024)
img: assets/img/p1.png
importance: 1
category: Research Projects
---
**Can first-order methods achieve the same performance as (established) second-order methods when used at high frequency in MPC?**

**Key words: Machine learning, HRI, Real-world Scenarios, Obstacle Avoidance, Human action prediction**

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/p1-1.jpg" title="p1-1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/p1-2.jpg" title="p1-2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- Proposed HRI demonstrations, showcasing real-world scenarios where a human and a robot share a common workspace.
- Developed an obstacle avoidance controller using DDP with customized soft constraints to avoid the predicted human action target.
- Integrated the algorithm with controllers for obstacle avoidance and reaching, then successfully deployed the combined system on a UR10e for real-world human-robot interaction (HRI) demonstrations.

