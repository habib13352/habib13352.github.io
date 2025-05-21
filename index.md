---
layout: default
title: Home
---

<section class="hero">
  <!-- ![Headshot](/assets/img/headshot.jpg){: .avatar } -->
  <h1>Hi, I’m Hamza</h1>
  <p>EET Graduate • Maker • Python Dev</p>
</section>

<section class="about">
  <h2>About Me</h2>
  <p>
    I build Python games, design CNC machines, and love embedded systems.<br>
    Check out my projects below!
  </p>
  <!-- <a href="/contact" class="link">Contact me</a> -->
</section>

<section class="projects">
  <h2>Projects</h2>
  {% for p in site.data.projects %}
  <div class="project-card">
    <h3>{{ p.title }} <small>({{ p.year }})</small></h3>
    <p>{{ p.description }}</p>
    <a href="{{ p.repo }}" target="_blank">Code</a>
    {% if p.demo %} • <a href="{{ p.demo }}" target="_blank">Demo</a>{% endif %}
  </div>
  {% endfor %}
</section>