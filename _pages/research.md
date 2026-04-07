---
layout: about
title: research
subtitle: Postdoctoral Research, Institute of Fluid Dynamics, ETH Zurich
nav: false
permalink: /

profile:
  align: right
  image: danielruth_headshot.jpg
  image_circular: false # crops the image to make it circular
  more_info: >

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Postdoctoral Researcher in the [Coletti Group](https://ifd.ethz.ch/research/group-coletti.html), which is part of the [Institute of Fluid Dynamics](https://ifd.ethz.ch/) at ETH Zurich. During my PhD, I studied the dynamics of **gas bubbles** in **turbulence** in the [Deike Lab](https://ldeike.princeton.edu/) at Princeton University, with applications to gas transfer at the ocean surface.

Broadly, I am interested in **multiphase turbulent flows** and the **experimental and numerical techniques** used to study them.

---

### Turbulence under wind-driven waves

The wind-driven shear flow beneath the ocean surface is impacted by wind-generated waves which propagate overhead. I study the turbulent characteristics of these flumes in the wind-water-wave flume at ETH Zurich using techniques like particle image velocimetry and laser-induced fluorescence.

<video autoplay loop muted playsinline width="100%">
  <source src="assets/video/ux_decomposed.mp4" type="video/mp4">
</video>

The video above shows the velocity field beneath wind-driven waves, which can be decomposed into a depth-dependent mean flow, orbital motions, and turbulence.


**Related Publications:**
<div class="publications">
  {% bibliography --group_by none -q @*[project=waves]* %}
</div>

---

### Surface deformations due to turbulence

Turbulence beneath a free surface imprints itself on the surface, causing deformations related to the vorticity (left) and degree of upwelling or downwelling (right).

<video autoplay loop muted playsinline width="100%">
  <source src="assets/video/pumppower50_nrowsmask2_z-2.0mm_ri0_VORTDIV.mp4" type="video/mp4">
</video>

In this experiment, the velocity beneath the surface is measured with **particle image velocimetry** and the surface elevation field is measured with **background-oriented schlieren**. The red and blue on the left shows the surface-normal vorticity and the green and purple on the right show the horizontal divergence of velocity. The surface morphology is represented by the curved lines, which come closer to each other at surface depressions (dimples) and farther apart at bulges in the surface.

---

### Turbulence near free surfaces

A free surface modifies the structure of a turbulent flow: vertical motions are inhibited by the presence of the surface, through which the fluid cannot pass. Further, my recent experimental work has shown that the turbulent cascade of energy is inhibited by the free surface. Approaching the surface, patches of energetic liquid are compressed vertically and extended horizontally, a "pancaking" effect which controls the inter-scale transfer of energy.

<video autoplay loop muted playsinline width="100%">
  <source src="assets/video/jacuzzi_wwt_together" type="video/mp4">
</video>

On the left in the animation above, **homogeneous turbulence** is generated in the bulk of a liquid by arrays of randomly-actuated synthetic jets; on the right, **wind** blown along the water surface in the ETH wind-wave flume induces both **surface gravity waves** and **turbulence** in the water. In both setups, **particle image velocimetry** is used to obtain the vorticity fields (shown in red and blue), and **laser-induced fluorescence** is used to locate the air-water interface (shown in cyan).

**Related Publications:**
<div class="publications">
  {% bibliography --group_by none -q @*[project=freesurface]* %}
</div>

---

### Bubbles in turbulence

In a turbulent flow, bubbles will break apart due to stresses from the surrounding turbulent liquid if they are large enough that surface tension is incapable of preventing severe deformations. Knowledge of the **dynamics of the break-ups** and the **distribution of bubble sizes** that are produced is important to modeling bubble-mediated gas transfer, as occurs with breaking waves on the ocean and in industrial bubble column reactors.

**Related Publications:**
<div class="publications">
  {% bibliography --group_by none -q @*[project=bubbles]* %}
</div>
