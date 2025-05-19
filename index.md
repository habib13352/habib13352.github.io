---
layout: default
title: Home
---

<section class="hero">
  ![Headshot](/assets/img/headshot.jpg){: .avatar }
  # Hi, I’m Hamza
  _EET Graduate • Maker • Python Dev_
</section>

<section class="about">
I build Python games, design CNC machines, and love embedded systems.  
Check out my projects below or [contact me](/contact){: .link }.
</section>

<section class="projects">
{% for p in site.data.projects %}
<div class="project-card">
  <h2>{{ p.title }} <small>({{ p.year }})</small></h2>
  <p>{{ p.description }}</p>
  <a href="{{ p.repo }}" target="_blank">Code</a>
  {% if p.demo %} • <a href="{{ p.demo }}" target="_blank">Demo</a>{% endif %}
</div>
{% endfor %}
</section>
