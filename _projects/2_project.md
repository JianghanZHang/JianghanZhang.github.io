---
layout: page
title: Accelerated gradient descent algorithm for MPC
description: 
img: assets/img/p2.jpg
importance: 2
---

**Can first-order methods achieve the same performance as (established) second-order methods when used at high frequency in MPC?**
**Key Words: Non-linear MPC, DDP, Accelerated Gradient Descent, C++, Real-robot deployment**

- Designed and Developed an accelerated gradient descent algorithm for real-time, high-frequency Nonlinear Model Predictive Control, achieving performance comparable to Differential Dynamic Programming (DDP) at 1 kHz. (LBR paper accpeted by UR 2024)
- Enhanced solver efficiency by systematically investigating various first-order optimization algorithms for non-linear MPC problems, resulting in an algorithm that is 4x faster than DDP per iteration.
- Reduced computation time to less than 1ms per control cycle for a 7-DoF manipulator by implementing advanced acceleration techniques (e.g. parallelization) in C++, enabling development on real-world manipulators at high frequencies.
- Deployed the algorithm on a real-world manipulator, achieving performance comparable to DDP at 1kHz, while robust to external disturbances.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/p2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    [https://github.com/JianghanZHang/AGD](https://github.com/JianghanZHang/AGD)
</div>
