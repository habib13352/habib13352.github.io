---
layout: single
title: "Hamza Habib"
permalink: /
author_profile: true
---

## About Me

Technologist and musician passionate about creative engineering. I build custom devices, teach guitar, and enjoy problem solving and learning. Actively looking for full-time roles in electronics, systems, or product engineering.

## Technical Stack

**Languages & Markup:** C, C++, Python, HTML/CSS, JavaScript (basics), G-code, XML  
**Microcontrollers & Platforms:** ESP32 (WROOM/S3), Arduino, FRDM-K64, LabJack (U9/U3 basics)  
**Tools & IDEs:** VS Code, Arduino IDE, PlatformIO, Git & GitHub, FluidNC, OpenCV, Pygame  
**Simulation & Design:** EAGLE CAD, OrCAD, MATLAB, Bambu Studio, Intel Quartas, Fusion 360

## Projects

{% for p in site.data.projects %}
- **{{ p.title }} ({{ p.year }})** – {{ p.description }} [Code]({{ p.repo }}){% if p.demo %} – [Demo]({{ p.demo }}){% endif %}
{% endfor %}

## Education

- **Seneca Polytechnic** – Adv. Diploma, Electronic Engineering Technology (2024)  
- **York University** – BFA Music (2022)

