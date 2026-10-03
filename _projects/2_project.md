---
layout: page
title: 48-12V Buck Converter 
description: Started December 2025
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---

Designed a 48V-to-12V synchronous buck converter to deliver clean power to the vehicle's low-voltage systems. This project was my introduction to the intense physical constraints of power electronics. I executed a 4-layer PCB layout utilizing an LM5148-Q1 controller and an LTC4364 surge stopper, navigating the complexities of component selection, thermal dissipation, and high-frequency switching noise. The board is currently manufactured and undergoing active bench testing, while I concurrently help the team architect a custom BLDC motor controller for the primary powertrain.

[Insert buck converter layout images here]

Technical Highlights:

Power Layout: Routed a 4-layer PCB with dedicated power/ground planes to minimize EMI and safely handle continuous high-current operation.

Component Integration: Selected and integrated MOSFETs, inductors, and surge-stopping load switches based strictly on datasheet thermal and electrical limits.

Validation: Utilized LTspice to simulate circuit stability and dynamic behavior under varying load conditions prior to physical manufacturing.