---
layout: archive
title: 
permalink: /experience/
redirect_from:
  - /cv/
  - /cv
author_profile: true
---
{% include base_path %}

<style>
  .experience-card {
    background: var(--global-bg-color, #fff);
    color: var(--global-text-color, inherit);
    border: 1px solid var(--global-border-color, #000);
    border-radius: 8px;
    padding: 16px;
    transition: transform 0.22s ease, box-shadow 0.22s ease, border-color 0.22s ease;
  }

  .experience-card:hover {
    transform: translateY(-3px);
    border-color: #005e7a;
    box-shadow: 0 8px 18px rgba(0, 94, 122, 0.16);
  }

  .experience-header {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-bottom: 18px;
    flex-wrap: wrap;
  }

  .experience-date {
    font-weight: 600;
    color: #004a43;
    white-space: nowrap;
  }

  .experience-duties {
    margin: 0;
  }

  .experience-duties li {
    margin-bottom: 6px;
  }
</style>

<div class="experience-card">
  <div class="experience-header">
    <img src="/images/iitr_logo.png" alt="IIT Roorkee Logo" style="width:70px; height:70px;">
    <div style="flex:1; min-width:240px;">
      <strong>Research Associate</strong><br>
      Indian Institute of Technology Roorkee, India<br>
      <em>Supervisor:</em> Prof. Yogendra Singh<br>
      <em>Project:</em> Enhancing Sustainability of RC Frame Buildings through Seismic Safety and Design Life Elongation Using GFRP Reinforcement
    </div>
    <div class="experience-date">
      Jun 2025 – Present
    </div>
  </div>

  <strong>Duties</strong>
  <ul class="experience-duties">
    <li>Conducting large-scale experimental testing of GFRP-reinforced members</li>
    <li>Developing phenomenological models to simulate the nonlinear response of GFRP-reinforced concrete columns</li>
    <li>Performing seismic risk and vulnerability assessment of GFRP-reinforced structures</li>
  </ul>
</div>
