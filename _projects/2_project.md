---
layout: page
title: 48-12V Buck Converter 
description: UCLA Supermileage Racing | Started December 2025
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---

I had the opportunity to design a 48V-to-12V synchronous buck converter to deliver clean power to the vehicle's low-voltage systems. This project was my introduction to the intense physical constraints of power electronics. I executed a 4-layer PCB layout utilizing an LM5148-Q1 controller and an LTC4364 surge stopper, navigating the complexities of component selection, thermal dissipation, and high-frequency switching noise. The board is currently manufactured and undergoing active bench testing, while I concurrently help the team architect a custom BLDC motor controller for the primary powertrain.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/buck-layout-1.jpg" title="Buck Converter and Load Switch Schematic" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/buck-layout-2.jpg" title="4-Layer PCB Layout" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Schematic design featuring the LM5148-Q1. Right: 4-layer PCB layout highlighting the dedicated ground and power planes.
</div>

**Technical Highlights:**

* **Power Layout:** Routed a 4-layer PCB with dedicated power/ground planes to minimize EMI and safely handle continuous high-current operation.
* **Component Integration:** Selected and integrated MOSFETs, inductors, and surge-stopping load switches based strictly on datasheet thermal and electrical limits.
* **Validation:** Utilized LTspice to simulate circuit stability and dynamic behavior under varying load conditions prior to physical manufacturing.