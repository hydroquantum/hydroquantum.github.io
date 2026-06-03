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

    <p>
      Please feel free to contact us at
      <a href="mailto:{{ site.email }}">{{ site.email }}</a>
      if you are interested.
    </p>

      <div class="actions">
        <a class="btn secondary" href="{{ '/projects/' | relative_url }}">Explore Projects</a>
        <a class="btn primary" href="{{ '/publications/' | relative_url }}">View Publications</a>
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
  <img
    src="{{ '/assets/images/home/QuantumComputingHydrology.png' | relative_url }}"
    alt="HydroQuantum research overview"
    class="home-overview-image"
  >

  <p class="lead">
    Advancing quantum computing applications in hydrology, irrigation,
    water quality, and large-scale environmental modeling.
  </p>
</div>