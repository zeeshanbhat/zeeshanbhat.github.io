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
    font-size: 0.9em;
    background: var(--global-bg-color, #fff);
    color: var(--global-text-color, inherit);
    border: 1px solid var(--global-border-color, #000);
    border-radius: 8px;
    padding: 14px;
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
    gap: 18px;
    margin-bottom: 16px;
    flex-wrap: wrap;
  }

  .experience-date {
    font-weight: 600;
    color: #005E7A;
    white-space: nowrap;
  }

  .experience-role,
  .experience-duties-title {
    color: #005E7A;
  }

  .experience-duties {
    margin: 0;
  }

  .experience-duties li {
    margin-bottom: 5px;
  }
</style>

<div class="experience-card">
  <div class="experience-header">
    <img src="/images/iitr_logo.png" alt="IIT Roorkee Logo" style="width:63px; height:63px;">
    <div style="flex:1; min-width:240px;">
      <strong class="experience-role">Research Associate</strong><br>
      Indian Institute of Technology Roorkee, India<br>
      <em>Supervisor:</em> Prof. Yogendra Singh<br>
      <em>Project:</em> Enhancing Sustainability of RC Frame Buildings through Seismic Safety and Design Life Elongation Using GFRP Reinforcement
    </div>
    <div class="experience-date">
      Jun 2025 – Present
    </div>
  </div>

  <strong class="experience-duties-title">Duties</strong>
  <ul class="experience-duties">
    <li>Conducting large-scale experimental testing of GFRP-reinforced members</li>
    <li>Developing phenomenological models to simulate the nonlinear response of GFRP-reinforced concrete columns</li>
    <li>Performing seismic risk and vulnerability assessment of GFRP-reinforced structures</li>
  </ul>
</div>

<div class="experience-card" style="margin-top:14px;">
  <div class="experience-header">
    <img src="/images/iitr_logo.png" alt="IIT Roorkee Logo" style="width:63px; height:63px;">
    <div style="flex:1; min-width:240px;">
      <strong class="experience-role">Ph.D. Research Scholar</strong><br>
      Indian Institute of Technology Roorkee, India<br>
      <em>Supervisor:</em> Prof. Yogendra Singh<br>
      <em>Thesis:</em> Experimental and Numerical Investigation of Seismic Behaviour of Masonry Infill Panels in RC Frame Buildings
    </div>
    <div class="experience-date">
      Jul 2018 – Mar 2025
    </div>
  </div>

  <strong class="experience-duties-title">Research Activities</strong>
  <ul class="experience-duties">
    <li>Conducted full-scale reversed cyclic experiments on masonry infill panels (in-plane and out-of-plane) in RC frames</li>
    <li>Applied Digital Image Correlation (DIC) for full-field strain and displacement measurement during large-scale tests</li>
    <li>Developed and calibrated nonlinear numerical models (diagonal strut, finite element) in OpenSees</li>
    <li>Performed seismic fragility and risk assessment of RC frame buildings with masonry infills</li>
  </ul>
</div>
