---
layout: page
title: Projects
permalink: /projects/
---



## A340-600 Vapor Cloud Visualization

![](/images/A346.png)

![](/images/A346_2.0.png)

![](/images/A346_3.0.png)

![](/images/A346_4.0.png)

<video controls autoplay loop muted width="800">
  <source src="{{ '/images/0000-0100.mp4' | relative_url }}" type="video/mp4">
</video>

This is my first aviation visualization project in Blender.

### Goal

To recreate the visible condensation cloud behind the wing of an Airbus A340-600 using Blender smoke, wind, and volume rendering tools.

### What I Have Done

- Imported an A340-600 model
- Created a gas domain
- Tested smoke inflow objects
- Added wind force fields
- Adjusted surface thickness for aircraft collision
- Tuned volume density and transparency
- Compared smoke-like behavior with airflow-like behavior
- Learned how cache, bake, and viewport rendering affect simulation results

### Problems Encountered

- Smoke spread too quickly
- The flow looked like fog instead of airflow
- Domain settings caused performance problems
- Volume density was sometimes too high or too low
- Collision thickness made the flow stay too far away from the wing

### Current Result

The project is still in an early visual simulation stage, but I now understand the basic Blender workflow for airflow-style visualization.
