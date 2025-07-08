---
layout: default
title:  // V //
---

<div class="hero">
  <h1>/ // V //</h1>
  <p class="subtitle">BRP</p>
  <div class="projects">
    {% for project in site.data.projects %}
      <div class="project-card">
        <a href="{{ project.url }}" target="_blank">
          <h2>{{ project.name }}</h2>
          <p>{{ project.description }}</p>
        </a>
      </div>
    {% endfor %}
  </div>
</div>
