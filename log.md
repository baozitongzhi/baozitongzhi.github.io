---
layout: page
title: Learning Log
permalink: /log/
---

# 2026/5/18 to 2026/5/28  A346 wing's airflow visualization


## 5/21

### Works

Learned the basic controls of Blender
Downloaded an Airbus 340-600 model from the Internet and imported it into Blender
Build a huge plane object in front of A346 for smoke generation
Build a domain with "inflow" property

### Problems

Failed to generate smoke from the inflow object
Smoke simulation did not appear correctly in the viewport
Limited understanding of Blender physics workflow
Smoke shape was unrealistic


## 5/22

### Works

Continued studying Blender smoke simulation workflow
Learned the cache and bake system for fluid simulations
Tested Replay, Modular, and Final cache modes
Adjusted smoke density, wind direction, and domain resolution
Experimented with volumetric rendering settings

### Problems

Smoke appeared in Solid View but disappeared in Render View
Rendered output was inconsistent with viewport preview


## 5/23

### Works

Rebuilt the smoke simulation system from scratch
Adjusted Wind Force Field parameters

### Problems

Smoke motion looked unnatural and chaotic


## 5/24

### Works

Began learning Blender rendering workflow
Studied the difference between Cycles and viewport rendering
Learned sampling and denoising settings

### Problems

Render times became extremely long
Hardware performance became a major limitation


## 5/25 to 5/27

### Works

Attempted to install additional Blender add-ons

### Problems

Plugin installation attempts were not always successful


## 5/28

### Works

Learned Blender camera workflow and scene composition
Learned how to align the camera to the current viewport
Began using F12 for final rendering
Learned image export and animation rendering workflow
Learned PNG sequence rendering and FFmpeg video export

### Problems

Viewport Render Image did not display the expected result
Final render output appeared empty despite visible viewport content
