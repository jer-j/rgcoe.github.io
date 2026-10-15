---
layout: page
title: Ship design optimization
description: modern tools to design modern naval vessels
img: assets/img/DDG71.jpg
importance: 1
category: current
giscus_comments: false
related_publications: false
images:
  slider: true
---

This project explores ship design optimization by combining physics-based modeling, simulation, and modern numerical methods to evaluate design tradeoffs for vessels that must perform a variety of missions that will evolve over the life the ship.
Within the optimization problem, we make use of models that provide analytic gradients, enabling fast gradient-based search and more efficient exploration of large design spaces.
When possible, mission-level fitness and cost are considered.

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/dtmb5415_body_plan_overlay.svg" title="DTMB5415 body plan overlay" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/dtmb5415_wave_resistance_vs_froude.svg" title="DTMB5415 wave resistance vs. Froude number" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/dtmb5415_open_water.svg" title="DTMB5415 open water propeller performance" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>
<div class="caption">
    DTMB5415 for initial (grey) and final design (blue).
</div>
