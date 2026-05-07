---
permalink: /
layout: archive

title: "Zeeshan Manzoor Bhat"
seo_title: "Zeeshan Manzoor Bhat"
excerpt: "Structural & Earthquake Engineering | IIT Roorkee"
author_profile: true
---

I am a Research Associate in the Department of Earthquake Engineering at the Indian Institute of Technology (IIT) Roorkee, India, working under <a href="https://www.iitr.ac.in/~EQ/yogenfeq" target="_blank" rel="noopener">Prof. Yogendra Singh</a>. My research focuses on using both large-scale experimental and numerical approaches to better understand how structures behave during earthquakes, with the goal of enhancing their performance, safety, and resilience. Through this work, I aim to contribute to the development of safer and more resilient infrastructure in earthquake-prone regions.

<div class="callout-award">
  <span class="callout-award__icon">🎉</span>
  <div class="callout-award__body">
    <strong>Canada Impact + Research Training Award</strong>
    I am honored to have received this award and will be joining <a href="https://smithengineering.queensu.ca/directory/faculty/amir-fam.html" target="_blank" rel="noopener">Prof. Amir Fam</a>'s research group at Queen's University, Canada, as a Postdoctoral Fellow. My research there will focus on developing energy-efficient and climate-resilient infrastructure, along with advancing seismic performance and design.
  </div>
</div>

<h3 class="section-heading">Research Interests</h3>

<div class="about-card-grid">
  <div class="about-hover-card interest-card">
    <span class="interest-card__icon">🏗️</span>
    <span class="interest-card__label">Large-scale experimental testing</span>
  </div>
  <div class="about-hover-card interest-card">
    <span class="interest-card__icon">📐</span>
    <span class="interest-card__label">Nonlinear structural modelling</span>
  </div>
  <div class="about-hover-card interest-card">
    <span class="interest-card__icon">🗺️</span>
    <span class="interest-card__label">Seismic hazard, risk, and vulnerability assessment</span>
  </div>
  <div class="about-hover-card interest-card">
    <span class="interest-card__icon">📊</span>
    <span class="interest-card__label">Performance-based earthquake engineering</span>
  </div>
  <div class="about-hover-card interest-card">
    <span class="interest-card__icon">🛡️</span>
    <span class="interest-card__label">Resilience-based seismic design</span>
  </div>
  <div class="about-hover-card interest-card">
    <span class="interest-card__icon">🔩</span>
    <span class="interest-card__label">Non-structural elements</span>
  </div>
  <div class="about-hover-card interest-card">
    <span class="interest-card__icon">🌱</span>
    <span class="interest-card__label">Energy efficiency and climate resilience</span>
  </div>
</div>

<h3 class="section-heading">Education</h3>

<div class="edu-timeline">
  <div class="edu-timeline__entry">
    <div class="edu-timeline__dot"></div>
    <div class="about-hover-card education-card">
      <img src="/images/iitr_logo.png" alt="IIT Roorkee Logo" style="width:70px; height:70px; flex-shrink:0;">
      <div style="flex:1;">
        <strong>Ph.D. in Structural and Earthquake Engineering</strong><br>
        Indian Institute of Technology Roorkee, India
      </div>
      <div style="font-weight:600; color:#005E7A; white-space:nowrap;">
        Jul 2018 – Mar 2025
      </div>
    </div>
  </div>

  <div class="edu-timeline__entry">
    <div class="edu-timeline__dot"></div>
    <div class="about-hover-card education-card">
      <img src="/images/nit_srinagar_logo.png" alt="NIT Srinagar Logo" style="width:70px; height:70px; flex-shrink:0;">
      <div style="flex:1;">
        <strong>M.Tech. in Structural Engineering</strong><br>
        National Institute of Technology Srinagar, India
      </div>
      <div style="font-weight:600; color:#005E7A; white-space:nowrap;">
        Jul 2016 – Jul 2018
      </div>
    </div>
  </div>

  <div class="edu-timeline__entry">
    <div class="edu-timeline__dot"></div>
    <div class="about-hover-card education-card">
      <img src="/images/nit_srinagar_logo.png" alt="NIT Srinagar Logo" style="width:70px; height:70px; flex-shrink:0;">
      <div style="flex:1;">
        <strong>B.Tech. in Civil Engineering</strong><br>
        National Institute of Technology Srinagar, India
      </div>
      <div style="font-weight:600; color:#005E7A; white-space:nowrap;">
        Jul 2012 – Jun 2016
      </div>
    </div>
  </div>
</div>

<div style="margin-top:28px; display:flex; gap:12px; flex-wrap:wrap; justify-content:center;">
  <button type="button" class="download-cv-btn" id="openCvModalBtn">
    Download CV
  </button>
</div>

<div class="cv-modal" id="cvModal" aria-hidden="true">
  <div class="cv-modal__content" role="dialog" aria-modal="true" aria-labelledby="cvModalTitle">
    <h4 id="cvModalTitle">Please enter your email to download my CV</h4>
    <p>Thanks for your interest. Share your email below and then continue to download the CV.</p>
    <form id="cvDownloadForm">
      <label class="cv-modal__field">
        <span>Email</span>
        <input type="email" name="email" required>
      </label>
      <div class="cv-modal__actions">
        <button type="button" class="cv-modal__close" id="closeCvModalBtn">Cancel</button>
        <button type="submit" class="cv-modal__submit">Continue to Download</button>
      </div>
    </form>
  </div>
</div>

<script>
  (function () {
    var openBtn  = document.getElementById('openCvModalBtn');
    var closeBtn = document.getElementById('closeCvModalBtn');
    var modal    = document.getElementById('cvModal');
    var form     = document.getElementById('cvDownloadForm');
    var cvPath   = '/files/CV_Zeeshan.pdf';

    if (!openBtn || !closeBtn || !modal || !form) { return; }

    function setModalState(isOpen) {
      modal.classList.toggle('is-open', isOpen);
      modal.setAttribute('aria-hidden', isOpen ? 'false' : 'true');
      document.body.style.overflow = isOpen ? 'hidden' : '';
    }

    openBtn.addEventListener('click',  function () { setModalState(true);  });
    closeBtn.addEventListener('click', function () { setModalState(false); });

    modal.addEventListener('click', function (e) {
      if (e.target === modal) { setModalState(false); }
    });

    form.addEventListener('submit', function (e) {
      e.preventDefault();
      if (!form.checkValidity()) { form.reportValidity(); return; }
      setModalState(false);
      window.open(cvPath, '_blank', 'noopener');
      form.reset();
    });
  })();
</script>
