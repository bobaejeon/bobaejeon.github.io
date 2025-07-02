---
layout: page
title: Visual Dubbing Pipeline (Video & Face Synthesis)
description: High-fidelity visual dubbing pipeline under few-shot constraints.
img: assets/img/vdub.jpg
importance: 1
category: Computer Vision
related_publications: true
---

A novel visual dubbing pipeline that balances lip-sync accuracy and realistic facial reenactment.
[Read the paper](https://diglib.eg.org/items/5653eca5-8a42-4410-b3a5-0f5cbf21ff5e) 

<!--    ----->
<!--    layout: page-->
<!--    title: project-->
<!--    description: a project with a background image-->
<!--    img: /assets/img/12.jpg-->
<!--    ----->

<!--<div class="row">-->
<!--    <div class="col-sm mt-3 mt-md-0">-->
<!--        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}-->
<!--    </div>-->
<!--    <div class="col-sm mt-3 mt-md-0">-->
<!--        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}-->
<!--    </div>-->
<!--    <div class="col-sm mt-3 mt-md-0">-->
<!--        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}-->
<!--    </div>-->
<!--</div>-->
<!--<div class="caption">-->
<!--    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.-->
<!--</div>-->
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
        {% include video.liquid loading="eager" path="assets/video/vdub.mp4" title="Demo video" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sample results, more to be found [here](https://diglib.eg.org/items/5653eca5-8a42-4410-b3a5-0f5cbf21ff5e)!
</div>

**Overview**
- Combines person-generic and person-specific methods for realistic visual dubbing
- Introduces a virtual dubber to capture expressive lip-sync with limited data
- Uses a full-head identity-swapping autoencoder to transfer face, hair, ears, and neck
- Eliminates artifacts like jitter and double chin from mouth-only approaches
- Achieves high visual quality and temporal consistency with short video inputs

<!--You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.-->
<!--Say you wanted to write a bit about your project before you posted the rest of the images.-->
<!--You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.-->
<!---->
<!--<div class="row justify-content-sm-center">-->
<!--    <div class="col-sm-8 mt-3 mt-md-0">-->
<!--        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}-->
<!--    </div>-->
<!--    <div class="col-sm-4 mt-3 mt-md-0">-->
<!--        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}-->
<!--    </div>-->
<!--</div>-->
<!--<div class="caption">-->
<!--    You can also have artistically styled 2/3 + 1/3 images, like these.-->
<!--</div>-->
<!---->
<!--The code is simple.-->
<!--Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).-->
<!--To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.-->
<!--Here's the code for the last row of images above:-->
<!---->
<!--{% raw %}-->
<!---->
<!--```html-->
<!--<div class="row justify-content-sm-center">-->
<!--  <div class="col-sm-8 mt-3 mt-md-0">-->
<!--    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}-->
<!--  </div>-->
<!--  <div class="col-sm-4 mt-3 mt-md-0">-->
<!--    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}-->
<!--  </div>-->
<!--</div>-->
<!--```-->
<!---->
<!--{% endraw %}-->
