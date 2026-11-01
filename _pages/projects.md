---
layout: page
title: Research
permalink: /projects/
description: Research directions and selected projects.
nav: true
nav_order: 2
---

{% assign research_projects = site.projects | where: "category", "research" | sort: "importance" %}

<div class="research-directions">
  {% for project in research_projects %}
    <section id="research-direction-{{ forloop.index }}" class="research-direction">
      <h2>{{ forloop.index }}. {{ project.title }}</h2>
      <div class="research-direction-content">{{ project.content }}</div>
    </section>
  {% endfor %}
</div>
