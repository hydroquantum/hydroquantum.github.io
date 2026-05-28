---
layout: default
title: Projects
permalink: /projects/
---

# Projects

<div class="grid two">
  {% for project in site.data.projects %}
    {% include project-card.html item=project %}
  {% endfor %}
</div>