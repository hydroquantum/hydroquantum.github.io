---
layout: default
title: Publications
permalink: /publications/
---

# Publications

<div class="grid two">
  {% for pub in site.data.publications %}
    {% include publication-card.html item=pub %}
  {% endfor %}
</div>