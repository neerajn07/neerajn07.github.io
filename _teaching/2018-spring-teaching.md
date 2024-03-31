---
title: "3D Compact Inversion of Gravity data"
collection: Research
type: "Project"
permalink: /research/2018-spring-teaching-1
venue: "Queen's University, Canada"
date: 2022-01-01 - 2023-01-01
location: "Kingston, Canada"
---

Title: 3D Compact Inversion of Gravity data
    <img src="/images/grav/grav_inv.gif" alt="Forward Response" style="width:50%; height:auto; display: block; margin: 0 auto;">

Abstract:
======
 Imaging and inversion techniques in potential field geophysics are crucial for estimating the distribution of source properties in 2D and 3D spaces. However, modeling potential field data often faces the challenge of non-uniqueness, necessitating constraining data to minimize uncertainty to recover the subsurface source distribution. Crucial information that can limit this uncertainty is found in the source dependency of different potential field data. This study explores the advantages of using the compact inversion technique to recover source distribution in 2D/3D spaces. This method focuses on minimizing the volume of the causative body through compactness weighting functions.

The functionality of these approaches is assessed with synthetic gravity and magnetic datasets for various complex models (e.g., multiple bodies at different depths and varying noise levels). Then, the recovered sources and property distribution, including density contrast and magnetization, are compared with the true model. The recovered model demonstrates superiority in delineating the shape and depth of the causative source. Furthermore, testing of the field data confirms the method's potential to produce compact and sharp inverse models of the subsurface. These findings underscore the importance of the compact inversion technique in potential field data, particularly in recovering the shape, size, geometry, and depth of ore body targets.

Introduction:
======
- Utilized a two-block model with a density contrast where each block has a density of 1 gm/cm³ set against a background density of 0 gm/cm³.
- The x-coordinates for the location of the two blocks are specified between 250-350m and 650-750m, positioned at a depth ranging from 100 to 200 meters.
- Calculated the forward response of the gravity model using the prism method to simulate the gravitational effect of the blocks.
- Implemented an inversion process with both model and depth weighting functions, which demonstrated a successful recovery of the original block model's parameters.

<h2>Results</h2>
<p>The analysis includes a synthetic model, its forward response, and the inverted model with the corresponding misfit. Each of these components is visualized in the figures below.</p>

<figure style="text-align: center; display: block; margin: 0 auto;">
    <img src="/images/grav/synthetic.png" alt="Synthetic Model" style="width:50%; height:auto; display: block; margin: 0 auto;">
    <figcaption style="display: block; margin-top: 0.5em;">Figure 1: Synthetic model representation.</figcaption>
</figure>

<figure style="text-align: center; display: block; margin: 0 auto;">
    <img src="/images/grav/grav_forward.png" alt="Forward Response" style="width:50%; height:auto; display: block; margin: 0 auto;">
    <figcaption style="display: block; margin-top: 0.5em;">Figure 2: Forward response of the synthetic model.</figcaption>
</figure>

<figure style="text-align: center; display: block; margin: 0 auto;">
    <img src="/images/grav/grav_inv.gif" alt="Inverted Model with Misfit" style="width:50%; height:auto; display: block; margin: 0 auto;">
    <figcaption style="display: block; margin-top: 0.5em;">Figure 3: Inverted model showing misfit analysis.</figcaption>
</figure>


Link to article:
======