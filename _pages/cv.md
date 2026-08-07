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


  /* ── Individual card ── */
  .experience-card {
    font-size: 0.9em;
    background: #fff;
    border: 1px solid #e2eaf0;
    border-left: 4px solid #005e7a;
    border-radius: 0 10px 10px 0;
    padding: 18px 20px 14px;
    margin-bottom: 22px;
    box-shadow: 0 2px 8px rgba(0, 94, 122, 0.07);
    transition: transform 0.22s ease, box-shadow 0.22s ease, border-left-color 0.22s ease;
  }


  .experience-card:hover {
    transform: translateX(4px);
    box-shadow: 0 6px 20px rgba(0, 94, 122, 0.15);
    border-left-color: #003f52;
  }

  /* ── Header row: logo + meta + badge ── */
  .experience-header {
    display: flex;
    align-items: flex-start;
    gap: 16px;
    margin-bottom: 14px;
    flex-wrap: wrap;
  }

  .experience-logo {
    width: 60px;
    height: 60px;
    object-fit: contain;
    border-radius: 6px;
    border: 1px solid #e2eaf0;
    padding: 3px;
    flex-shrink: 0;
    background: #f7fbfd;
  }

  .experience-meta {
    flex: 1;
    min-width: 200px;
  }

  .experience-role {
    display: block;
    font-size: 1.05em;
    font-weight: 700;
    color: #003f52;
    margin-bottom: 3px;
  }

  .experience-org {
    font-weight: 600;
    color: #005e7a;
    margin-bottom: 4px;
  }

  .experience-supervisor,
  .experience-project {
    color: #555;
    font-size: 0.92em;
    margin-bottom: 2px;
  }

  /* ── Date badge ── */
  .experience-date {
    display: inline-block;
    background: #e7f4f8;
    color: #005e7a;
    font-weight: 600;
    font-size: 0.82em;
    padding: 4px 10px;
    border-radius: 20px;
    white-space: nowrap;
    align-self: flex-start;
    border: 1px solid #b8dce8;
  }

  /* ── Duties section ── */
  .experience-duties-title {
    display: block;
    font-size: 0.85em;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    color: #005e7a;
    margin-bottom: 8px;
    padding-bottom: 4px;
    border-bottom: 1px dashed #b8dce8;
  }

  .experience-duties {
    margin: 0;
    padding-left: 18px;
  }

  .experience-duties li {
    margin-bottom: 5px;
    color: #333;
    line-height: 1.5;
  }

  .experience-duties li::marker {
    color: #005e7a;
  }
</style>

<div class="experience-timeline">


  <div class="experience-card">
    <div class="experience-header">
      <img class="experience-logo" src="/images/queens_logo.png" alt="Queen's University Logo">
      <div class="experience-meta">
        <strong class="experience-role">NSERC-CIRTA Postdoctoral Fellow</strong>
        <div class="experience-org">Queen's University, Kingston, Canada</div>
        <div class="experience-supervisor"><em>Supervisor:</em> Prof. Amir Fam</div>
        <div class="experience-project"><em>Project:</em> </div>
      </div>
      <span class="experience-date">Aug 2026 – Present</span>
    </div>
    <strong class="experience-duties-title">Duties</strong>
    <ul class="experience-duties">
    </ul>
  </div>

  <div class="experience-card">
    <div class="experience-header">
      <img class="experience-logo" src="/images/iitr_logo.png" alt="IIT Roorkee Logo">
      <div class="experience-meta">
        <strong class="experience-role">Research Associate</strong>
        <div class="experience-org">Indian Institute of Technology Roorkee, India</div>
        <div class="experience-supervisor"><em>Supervisor:</em> Prof. Yogendra Singh</div>
        <div class="experience-project"><em>Project:</em> Enhancing Sustainability of RC Frame Buildings through Seismic Safety and Design Life Elongation Using GFRP Reinforcement</div>
      </div>
      <span class="experience-date">Jun 2025 – June 2026</span>
    </div>
    <strong class="experience-duties-title">Duties</strong>
    <ul class="experience-duties">
      <li>Conducting large-scale experimental testing of GFRP-reinforced members</li>
      <li>Developing phenomenological models to simulate the nonlinear response of GFRP-reinforced concrete columns</li>
      <li>Performing seismic risk and vulnerability assessment of GFRP-reinforced structures</li>
    </ul>
  </div>

  <div class="experience-card">
    <div class="experience-header">
      <img class="experience-logo" src="/images/iitr_logo.png" alt="IIT Roorkee Logo">
      <div class="experience-meta">
        <strong class="experience-role">Ph.D. Research Scholar</strong>
        <div class="experience-org">Indian Institute of Technology Roorkee, India</div>
        <div class="experience-supervisor"><em>Supervisor:</em> Prof. Yogendra Singh</div>
        <div class="experience-project"><em>Thesis:</em> Experimental and Numerical Investigation of Seismic Behaviour of Masonry Infill Panels in RC Frame Buildings</div>
      </div>
      <span class="experience-date">Jul 2018 – Mar 2025</span>
    </div>
    <strong class="experience-duties-title">Research Activities</strong>
    <ul class="experience-duties">
      <li>Conducted full-scale reversed cyclic experiments on masonry infill panels (in-plane and out-of-plane) in RC frames</li>
      <li>Applied Digital Image Correlation (DIC) for full-field strain and displacement measurement during large-scale tests</li>
      <li>Developed and calibrated nonlinear numerical models (diagonal strut, finite element) in OpenSees</li>
      <li>Performed seismic fragility and risk assessment of RC frame buildings with masonry infills</li>
    </ul>
  </div>

</div>
