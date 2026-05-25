---
layout: page
title: Learning Log
permalink: /log/
---

# Learning Log

## My First Blender Airflow Experiment

I started this project because I noticed the condensation cloud behind a Lufthansa A340-600 I photographed before. I wanted to see if I could recreate something similar in Blender.

At first, I honestly thought airflow visualization would be simple. I created a large plane in front of the aircraft and used it to generate smoke. Technically it worked, but the result looked more like fog filling the entire scene than actual airflow.

So I tried turning the plane into multiple stripes instead. That already looked much better. The smoke finally started to resemble separate flow lines instead of one giant cloud.

Later, I replaced the stripes with many small lined cubes. That was the first moment where the flow started to feel more directional and aerodynamic instead of random smoke.

I also spent a ridiculous amount of time trying to understand why the smoke kept exploding, disappearing, or spreading everywhere. Eventually I realized most of the problems came from things like:
- wind strength
- collision thickness
- domain size
- rebaking cache
- smoke density vs material density

One thing that surprised me was how different visual smoke simulation is from real CFD. Before this project, I thought adding smoke automatically meant “airflow.” But now I understand that smoke is only a visualization tool. Without a proper flow field, it just behaves like drifting fog.

I am still very early in this process, but this project already changed the way I look at aircraft wake turbulence and condensation clouds.
