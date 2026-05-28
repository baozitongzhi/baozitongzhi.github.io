---
layout: page
title: Learning Log
permalink: /log/
---

# A346 Wing's Airflow Visualization

---

## 5/21

### Work Completed

- Learned the basic controls of Blender
- Downloaded an Airbus A340-600 model from the Internet and imported it into Blender
- Built a huge plane object in front of A346 for smoke generation
- Built a domain with "inflow" property

### Problems Encountered

- Failed to generate smoke from the inflow object
- Smoke simulation did not appear correctly in the viewport
- Limited understanding of Blender physics workflow
- Smoke shape was unrealistic

### Solutions

- Rebuilt the smoke inflow system multiple times
- Adjusted domain scale and inflow settings
- Learned the basic Mantaflow simulation workflow
- Tested different smoke density and resolution settings

---

## 5/22

### Work Completed

- Continued studying Blender smoke simulation workflow
- Learned the cache and bake system for fluid simulations
- Tested Replay, Modular, and Final cache modes
- Adjusted smoke density, wind direction, and domain resolution
- Experimented with volumetric rendering settings

### Problems Encountered

- Smoke appeared in Solid View but disappeared in Render View
- Rendered output was inconsistent with viewport preview

### Solutions

- Checked material and volume shader settings
- Rebuilt the simulation domain and rebaked the cache
- Adjusted render visibility and volume rendering parameters
- Compared viewport shading with Cycles render output

---

## 5/23

### Work Completed

- Rebuilt the smoke simulation system from scratch
- Adjusted Wind Force Field parameters

### Problems Encountered

- Smoke motion looked unnatural and chaotic

### Solutions

- Tested different wind strengths and directions
- Modified inflow positioning and smoke scale
- Reduced turbulence and adjusted domain proportions

---

## 5/24

### Work Completed

- Began learning Blender rendering workflow
- Studied the difference between Cycles and viewport rendering
- Learned sampling and denoising settings

### Problems Encountered

- Render times became extremely long
- Hardware performance became a major limitation

### Solutions

- Reduced render samples and enabled denoising
- Experimented with lower render resolutions
- Attempted GPU acceleration and rendering optimization

---

## 5/25 to 5/27

### Work Completed
- Attempted to install additional Blender add-ons

### Problems Encountered

- Plugin installation attempts were not always successful
- Some add-ons were incompatible with the Blender version

### Solutions

- Tested different Blender versions
- Reinstalled Blender and rebuilt the project environment
- Researched compatibility issues and alternative workflows

---

## 5/28

### Work Completed

- Learned Blender camera workflow and scene composition
- Learned how to align the camera to the current viewport
- Began using F12 for final rendering
- Learned image export and animation rendering workflow
- Learned PNG sequence rendering and FFmpeg video export

### Problems Encountered

- Viewport Render Image did not display the expected result
- Final render output appeared empty despite visible viewport content
- Video rendering was interrupted due to an unexpected shutdown

### Solutions

- Learned the difference between viewport rendering and final rendering
- Corrected camera positioning and render visibility settings
- Switched from direct MP4 rendering to PNG image sequence rendering
- Successfully reassembled rendered frames into a final video
```
