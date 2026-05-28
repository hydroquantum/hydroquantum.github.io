---
layout: default
title: Team
permalink: /team/
---

# Team

<div class="grid two">
{% for person in site.data.team %}
  <article class="card">
    {% if person.image %}
      <img
        class="profile-image"
        src="{{ person.image | relative_url }}"
        alt="{{ person.name }}"
      >
    {% endif %}
    <div class="profile-top">
      <div>
        <h2 style="margin:0 0 6px;">{{ person.name }}</h2>
        <span>{{ person.role }}</span>
      </div>
    </div>
    <!-- <p>{{ person.bio }}</p> -->
    <div class="team-bio">
      {{ person.bio | newline_to_br }}
    </div>
    <div class="inline-links">
      {% if person.github != blank %}<a href="{{ person.github }}" target="_blank" rel="noreferrer">GitHub</a>{% endif %}
      {% if person.scholar != blank %}<a href="{{ person.scholar }}" target="_blank" rel="noreferrer">Google Scholar</a>{% endif %}
    </div>
  </article>
{% endfor %}
</div>
