---
layout: page
title: IEEE Micromouse 
description: Project Member | September 2025 - May 2026
img: assets/img/7.jpg
importance: 3
category: work
---

I collaborated with my peers to engineer an autonomous, maze-solving robot from the ground up. This project served as my foundational experience in embedded systems, requiring tight integration between physical circuit design and C-based control logic to successfully navigate a physical race course.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mouse-pcb.jpg" title="Micromouse PCB" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mouse-robot.jpg" title="Assembled Micromouse" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Custom STM32 PCB layout. Right: Fully assembled autonomous maze-solving robot.
</div>

**Technical Highlights:**

* **Hardware Design:** Executed schematic capture and PCB layout integrating an STM32 microcontroller, H-bridge motor drivers, voltage regulators, and IR sensors.
* **Manufacturing:** Fully assembled and surface-mount soldered the custom PCB.
* **Embedded Software:** Programmed the STM32 in C to execute closed-loop PID motor control and a flood-fill pathfinding algorithm based on real-time IR sensor telemetry.