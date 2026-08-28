---
title: "Home"
description: "Lead Data Scientist working at the intersection of time series, geospatial data, statistics, machine learning and AI."
---

<p class="eyebrow">Lead Data Scientist · Time Series · Geospatial Data · Statistics · ML & AI</p>

<style>
  .site-header a {
    color: #6b7280;
  }
</style>

<header class="site-header">
    <a href="{{ '/about/' | relative_url }}">About</a>
    <a href="{{ '/research/' | relative_url }}">Research</a>
    <a href="{{ '/publications/' | relative_url }}">Publications</a>
    <a href="{{ '/work/' | relative_url }}">Work</a>
  </nav>
</header>

<section class="section intro">
  <p>I turn complex <strong>temporal and spatial data into models, insights, and decisions</strong>.</p>
  <p>My work sits at the intersection of <strong>advanced statistics, machine learning, and AI</strong> — with a particular interest in understanding <em>how things change over time and across space</em>.</p>
</section>

<section class="hero">
  
  <h1>Understanding complex systems through data.</h1>
  <p class="lead">
    I develop probabilistic and machine-learning methods for understanding systems
    that evolve across <strong>time, space and uncertainty</strong>.
  </p>
  <div class="actions">
    <a class="button primary" href="{{ '/work/' | relative_url }}">Selected work</a>
    <a class="button" href="{{ '/publications/' | relative_url }}">Publications</a>
  </div>
</section>

<section class="section intro-grid">
  <div>
    <p class="eyebrow">What I work on</p>
    <h2>Statistics for messy, dynamic systems.</h2>
  </div>
  <div class="prose">
    <p>
      My background is in computational statistics and scientific research, with
      work spanning climate dynamics, probabilistic modelling, uncertainty
      quantification and complex systems.
    </p>
    <p>
      Today I combine advanced statistics with machine learning and AI to turn
      temporal and spatial data into useful models, insights and decisions.
    </p>
  </div>
</section>

<section class="section">
  <div class="section-heading">
    <div>
      <p class="eyebrow">Selected work</p>
      <h2>From questions to models.</h2>
    </div>
    <a href="{{ '/work/' | relative_url }}">View all →</a>
  </div>

  <div class="project-grid">
    {% for project in site.projects limit:3 %}
      <a class="project-card" href="{{ project.url | relative_url }}">
        <span class="project-number">{{ forloop.index | prepend: '0' }}</span>
        <h3>{{ project.title }}</h3>
        <p>{{ project.excerpt | strip_html | truncate: 150 }}</p>
        <span class="card-link">Explore project →</span>
      </a>
    {% endfor %}
  </div>
</section>

<section class="section split">
  <div>
    <p class="eyebrow">Research</p>
    <h2>A scientific foundation.</h2>
  </div>
  <div class="prose">
    <p>
      My research has focused on extracting reliable information from complex,
      noisy and uncertain systems. That includes Bayesian inference, time-series
      analysis, sensitivity analysis and scientific computing.
    </p>
    <a class="text-link" href="{{ '/research/' | relative_url }}">Explore research →</a>
  </div>
</section>

<section class="section">
  <div class="section-heading">
    <div>
      <p class="eyebrow">Publications</p>
      <h2>Selected scientific work.</h2>
    </div>
    <a href="{{ '/publications/' | relative_url }}">Full list →</a>
  </div>

  <div class="publication-list">
    <article>
      <span>2022 · Quaternary Science Reviews</span>
      <h3>Bayesian inference about climate transitions</h3>
      <p>Time series · Bayesian inference · Climate dynamics</p>
    </article>
  </div>
</section>

<section class="section contact">
  <p class="eyebrow">Let's connect</p>
  <h2>Interested in time series, geospatial modelling, statistics or applied AI?</h2>
  <p>
    I'm always happy to exchange ideas, discuss interesting problems, or talk
    about what works — and what definitely doesn't.
  </p>
  <div class="actions">
    <a class="button primary" href="mailto:dinschuetz@web.de">Get in touch</a>
    <a class="button" href="https://github.com/pyatwork">GitHub</a>
    <a class="button" href="https://www.linkedin.com/in/USERNAME/">LinkedIn</a>
  </div>
</section>

<footer class="site-note">
  <p>© 2026 Nadine Berner. Built with Jekyll and GitHub Pages ❤️</p>
</footer>
