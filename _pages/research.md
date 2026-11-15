---
layout: page
title: Research
permalink: /research/
description:
nav: true
nav_order: 1
---

## Research Statement

[PLACEHOLDER] About 150 words in the first person. Problem, approach, and why it matters.

## Research Trajectory

<ol class="research-trajectory">
{% for node in site.data.trajectory %}
  <li class="trajectory-node{% if node.open %} trajectory-node--open{% endif %}">
    <strong>{{ node.question }}</strong>{% if node.caption %}<br><span class="text-muted">{{ node.caption }}</span>{% endif %}
  </li>
{% endfor %}
</ol>

## Traversability Prediction {#traversability-prediction}

[PLACEHOLDER] Three-line summary and a figure.

## Terramechanics & Granular Physics {#terramechanics}

[PLACEHOLDER] Three-line summary and a figure.

## Adaptive Locomotion Hardware {#adaptive-locomotion-hardware}

[PLACEHOLDER] Figure or video of the deployable wheel.

**Soft deployable airless wheel.** A robust, soft deployable wheel designed for safe "direct drop" deployment, aimed at intact exploration of lunar lava tubes. Developed with the Unmanned Exploration Laboratory (UEL), KASI, KARI, and Hanyang University.

- Paper. [Soft deployable airless wheel for lunar lava tube intact exploration](https://doi.org/10.1126/scirobotics.adx2549), _Science Robotics_, 2025
- Award. Best Poster Award, Intelligent Space Robotics and Systems Workshop, ICRA 2026
- Media. [CNN Tech for Good](https://edition.cnn.com/science/korea-origami-inspired-rover-wheels-explore-moon-hnk-spc), 2026

## Space Robotics {#space-robotics}

[PLACEHOLDER] Three-line summary and a figure.

- Review. [Advances and Trends in Space Robotics Technology Development and Research](https://doi.org/10.5139/JKSAS.2025.53.10.1083), _JKSAS_, 2025
- Simulation. Lunar subsurface cave exploration with a flexible-wheeled rover and a carrier rover with a deployable manipulator. Silver Prize, 2026 RecurDyn Simulation Competition
