---
layout: page
title: Visual Dubbing Pipeline (Video & Face Synthesis)
description: High-fidelity visual dubbing pipeline under few-shot constraints.
img: assets/img/vdub.jpg
importance: 1
category: Computer Vision
---

A novel visual dubbing pipeline that balances lip-sync accuracy and realistic facial reenactment.
[Read the paper](https://diglib.eg.org/items/5653eca5-8a42-4410-b3a5-0f5cbf21ff5e) 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/vdub.jpg" title="Overall pipeline: inference" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of the pipeline in inference time. More details can be found on the paper.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/vdub.mp4" title="Demo video" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Sample results, more to be found <a href="https://diglib.eg.org/items/5653eca5-8a42-4410-b3a5-0f5cbf21ff5e">here</a>!
</div>

**Overview**
- Combines person-generic and person-specific methods for realistic visual dubbing
- Introduces a virtual dubber to capture expressive lip-sync with limited data
- Uses a full-head identity-swapping autoencoder to transfer face, hair, ears, and neck
- Eliminates artifacts like jitter and double chin from mouth-only approaches
- Achieves high visual quality and temporal consistency with short video inputs
