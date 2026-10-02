---
layout: page
title: The Aerospace CorporationAnalog and Power Systems Intern 
description: Summer 2026
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

This experience fundamentally shifted my engineering perspective from theoretical math to physical hardware. I spent the summer bridging the gap between ideal circuit calculations and real-world physical metrology, specifically focusing on the behaviors of discrete 3-terminal active devices. My workflow centered on simulating baseline behaviors and then moving directly to the bench to physically debug and confirm those calculations using high-end instrumentation (Oscilloscopes, Omicron Bode 100, Source Measure Units). Beyond physical circuits, I also gained exposure to industry-standard power systems modeling by analyzing the state of charge in nickel-hydrogen batteries. 

Key Projects & Technical Highlights:
COTS pFET Radiation Tester: Evaluated COTS p-channel MOSFETs for rad-hard applications by designing a multi-channel PCB test fixture and extracting baseline $I-V$ curves via SMU.

Impedance Buffering: Eliminated loading effects on a Schmitt trigger ring oscillator by white-wiring an emitter-follower stage to buffer the voltage reference.

EMI Filters: Validated high-frequency noise attenuation of a contractor-designed EMI filter by prototyping the circuit and extracting frequency responses using a Bode 100.

B-H Curve Tracer: Constructed a two-stage linear transconductance amplifier (pre-amp and Darlington-pair) to drive controlled current for magnetic core trace extraction.
Battery Power Management: Modeled Nickel-Hydrogen State of Charge (SOC) behavior.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
