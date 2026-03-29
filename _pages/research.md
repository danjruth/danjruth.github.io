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
    <p>daruth at ethz.ch</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
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

Welcome to my research portfolio. Below are some of my recent projects.

---

### Turbulence near free surfaces

A free surface such as the ocean-atmosphere interface will modify the structure of a turbulent flow, and wind acting at a free surface can generate turbulence in the water below.

I study free surfaces experimentally: on the left in the animation below, **homogeneous turbulence** is generated in the bulk of a liquid by arrays of randomly-actuated synthetic jets; on the right, **wind** blown along the water surface in a long channel induces both **surface gravity waves** and **turbulence** in the water. In both setups, **particle image velocimetry** is used to obtain the vorticity fields (shown in red and blue), and **laser-induced fluorescence** is used to locate the air-water interface (shown in cyan).

**Related Publications:**
<div class="publications">
  {% bibliography -q @*[project=freesurfaces]* %}
</div>
