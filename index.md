---
layout: home
title: Home
---

<div class="hero">
  <div class="hero-grid">
    <section class="hero-card">
        
      <!-- <img
        src="{{ '/assets/images/logo/Hydroquantum.jpg' | relative_url }}"
        alt="HydroQuantum Logo"
        class="hero-logo"
      > -->
        
      <p class="kicker">{{ site.tagline }}</p>
      
      <h1>HydroQuantum</h1>
      
      <p>
        {{ site.description }}
      </p>

      <div class="actions">
        <a class="btn primary" href="{{ '/publications/' | relative_url }}">View Publications</a>
        <a class="btn secondary" href="{{ '/projects/' | relative_url }}">Explore Projects</a>
      </div>
    </section>

    <!-- <aside class="hero-card hero-side">
      <div class="mini-stat">
        <strong>2</strong>
        <span>published papers</span>
      </div>
      <div class="mini-stat">
        <strong>1</strong>
        <span>review paper under review</span>
      </div>
      <div class="mini-stat">
        <strong>1</strong>
        <span>active CONUS-scale QGNN effort</span>
      </div>
      <div class="mini-stat">
        <strong>2</strong>
        <span>open-source packages</span>
      </div>
    </aside> -->
    
  </div>
</div>

<div class="section">
  <h2>Featured publications</h2>
    
  <div class="grid two">
    {% for pub in site.data.publications %}
      {% include publication-card.html item=pub %}
    {% endfor %}
  </div>
</div>

<div class="section">
  <h2>Current projects</h2>

  <div class="grid two">
    {% for project in site.data.projects %}
      {% include project-card.html item=project %}
    {% endfor %}
  </div>
</div>