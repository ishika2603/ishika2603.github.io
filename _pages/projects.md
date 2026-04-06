---
layout: page
title: projects
permalink: /projects/
description: Some side projects for work and fun!
nav: true
nav_order: 3
---

<div class="projects projects--list">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  {% for project in sorted_projects %}
    {% include projects_list_item.liquid %}
  {% endfor %}
</div>
