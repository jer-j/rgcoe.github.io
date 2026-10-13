---
layout: page
title: Ship design optimization
description: modern tools to design modern naval vessels
img: assets/img/DDG71.jpg
importance: 1
category: current
giscus_comments: false
related_publications: false
---

This project explores ship design optimization by combining physics-based modeling, simulation, and modern numerical methods to evaluate design tradeoffs for vessels that must perform a variety of missions that will evolve over the life the ship.
Within the optimization problem, we make use of models that provide analytic gradients, enabling fast gradient-based search and more efficient exploration of large design spaces.
When possible, mission-level fitness and cost are considered.

<div class="row">
    <div class="col-sm-6 mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dtmb5415_body_plan_overlay.svg" title="X-Spar buoy at sea" class="img-fluid rounded z-depth-1" height="400" max-width="100%" %}
    </div>
    <div class="col-sm-6 mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dtmb5415_wave_resistance_vs_froude.svg" title="X-Spar buoy crane lift" class="img-fluid rounded z-depth-1" height="400" max-width="100%" %}
    </div>
</div>
<div class="caption">
    DTMB5415 for initial (grey) and final design (blue).
</div>
