---
permalink: /
layout: archive

title: "Zeeshan Manzoor Bhat"
seo_title: "Zeeshan Manzoor Bhat"
excerpt: "Structural & Earthquake Engineering | IIT Roorkee"
author_profile: true
---

I am a Research Associate in the Department of Earthquake Engineering at the Indian Institute of Technology (IIT) Roorkee, India, working under <a href="https://www.iitr.ac.in/~EQ/yogenfeq" target="_blank" rel="noopener">Prof. Yogendra Singh</a>. My research focuses on using both large-scale experimental and numerical approaches to better understand how structures behave during earthquakes, with the goal of enhancing their performance, safety, and resilience. Through this work, I aim to contribute to the development of safer and more resilient infrastructure in earthquake-prone regions.

<div style="background:linear-gradient(135deg,#fff8ec 0%,#fff3e0 100%);border:2px solid #e8a020;border-radius:14px;padding:18px 22px;margin:20px 0;display:flex;gap:16px;align-items:flex-start;box-shadow:0 4px 14px rgba(232,160,32,0.12);">
  <span style="font-size:2rem;line-height:1;flex-shrink:0;">🎉</span>
  <div>
    <div style="font-weight:700;font-size:1.08rem;color:#c45c00;margin-bottom:6px;">Canada Impact + Research Training Award</div>
    <div>I am honored to have received this award and will be joining <a href="https://smithengineering.queensu.ca/directory/faculty/amir-fam.html" target="_blank" rel="noopener">Prof. Amir Fam</a>'s research group at Queen's University, Canada, as a Postdoctoral Fellow. My research there will focus on developing energy-efficient and climate-resilient infrastructure, along with advancing seismic performance and design.</div>
  </div>
</div>

<!-- ===== STATS BAR ===== -->
<div class="stats-bar">
  <div class="stats-bar__item">
    <span class="stats-bar__number" data-target="10">0</span>
    <span class="stats-bar__label">Publications</span>
  </div>
  <div class="stats-bar__item">
    <span class="stats-bar__number" data-target="7">0</span>
    <span class="stats-bar__label">Years of Research</span>
  </div>
  <div class="stats-bar__item">
    <span class="stats-bar__number" data-target="14">0</span>
    <span class="stats-bar__label">Full-Scale Tests</span>
  </div>
  <div class="stats-bar__item">
    <span class="stats-bar__number" data-target="2">0</span>
    <span class="stats-bar__label">Funded Projects</span>
  </div>
</div>

<style>
  /* ===== STATS BAR ===== */
  .stats-bar {
    display: flex;
    flex-wrap: wrap;
    gap: 0;
    margin: 24px 0 28px;
    border: 1px solid #E6EBF2;
    border-radius: 14px;
    overflow: hidden;
    background: #fff;
    box-shadow: 0 4px 16px rgba(31, 58, 95, 0.07);
  }

  .stats-bar__item {
    flex: 1 1 120px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 20px 12px;
    border-right: 1px solid #E6EBF2;
    transition: background 0.2s;
  }

  .stats-bar__item:last-child {
    border-right: none;
  }

  .stats-bar__item:hover {
    background: #f0f7fa;
  }

  .stats-bar__number {
    font-size: 2rem;
    font-weight: 700;
    color: #005E7A;
    line-height: 1;
    margin-bottom: 4px;
  }

  .stats-bar__label {
    font-size: 0.75rem;
    color: #5F7FA3;
    font-weight: 600;
    letter-spacing: 0.5px;
    text-align: center;
  }

  @media (max-width: 540px) {
    .stats-bar {
      flex-direction: row;
    }
    .stats-bar__item {
      flex: 1 1 45%;
      border-bottom: 1px solid #E6EBF2;
    }
    .stats-bar__item:nth-child(even) {
      border-right: none;
    }
  }

  /* ===== RESEARCH INTEREST CARDS ===== */
  .about-card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 12px;
    margin: 14px 0 22px;
  }

  .about-hover-card {
    background: var(--global-bg-color, #fff);
    color: var(--global-text-color, inherit);
    border: 1px solid var(--global-border-color, #E6EBF2);
    padding: 14px 16px;
    border-radius: 10px;
    font-weight: 400;
    font-family: var(--global-font-family, inherit);
    transition: transform 0.22s ease, box-shadow 0.22s ease, border-color 0.22s ease;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .about-hover-card:hover {
    transform: translateY(-3px);
    border-color: #005e7a;
    box-shadow: 0 8px 18px rgba(0, 94, 122, 0.16);
  }

  .about-hover-card .card-icon {
    font-size: 1.4rem;
    flex-shrink: 0;
    line-height: 1;
  }

  .education-card {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-bottom: 16px;
    padding: 14px;
  }

  .download-cv-btn {
    display: inline-block;
    background: #005e7a;
    color: #fff;
    padding: 10px 16px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: 600;
    border: 0;
    cursor: pointer;
    transition: transform 0.22s ease, box-shadow 0.22s ease, background-color 0.22s ease;
  }

  .download-cv-btn:hover {
    background: #00789b;
    transform: translateY(-2px);
    box-shadow: 0 9px 16px rgba(0, 94, 122, 0.28);
  }

  /* ===== NEWS SECTION ===== */
  .news-timeline {
    margin: 14px 0 28px;
    position: relative;
    padding-left: 20px;
  }

  .news-timeline::before {
    content: '';
    position: absolute;
    left: 5px;
    top: 6px;
    bottom: 6px;
    width: 2px;
    background: linear-gradient(180deg, #005E7A 0%, #E6EBF2 100%);
    border-radius: 2px;
  }

  .news-item {
    position: relative;
    margin-bottom: 18px;
    padding-left: 20px;
  }

  .news-item::before {
    content: '';
    position: absolute;
    left: -19px;
    top: 6px;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: #005E7A;
    border: 2px solid #fff;
    box-shadow: 0 0 0 2px #005E7A;
  }

  .news-item__date {
    font-size: 0.72rem;
    font-weight: 700;
    color: #005E7A;
    letter-spacing: 0.8px;
    text-transform: uppercase;
    margin-bottom: 3px;
  }

  .news-item__text {
    font-size: 0.9rem;
    color: var(--global-text-color, #333);
    line-height: 1.5;
  }

  /* ===== CV MODAL ===== */
  .cv-modal {
    position: fixed;
    inset: 0;
    background: rgba(0, 0, 0, 0.45);
    display: none;
    align-items: center;
    justify-content: center;
    z-index: 1200;
    padding: 20px;
  }

  .cv-modal.is-open {
    display: flex;
  }

  .cv-modal__content {
    width: min(100%, 420px);
    background: var(--global-bg-color, #fff);
    border-radius: 12px;
    border: 1px solid var(--global-border-color, #d1d5db);
    box-shadow: 0 18px 35px rgba(0, 0, 0, 0.2);
    padding: 18px;
  }

  .cv-modal__content h4 {
    margin: 0 0 8px;
    color: #005e7a;
  }

  .cv-modal__content p {
    margin: 0 0 14px;
    font-size: 0.94rem;
  }

  .cv-modal__field {
    display: block;
    margin-bottom: 12px;
  }

  .cv-modal__field span {
    display: inline-block;
    margin-bottom: 6px;
    font-weight: 600;
    font-size: 0.9rem;
  }

  .cv-modal__field input,
  .cv-modal__field textarea {
    width: 100%;
    padding: 9px 10px;
    border: 1px solid #cbd5e1;
    border-radius: 8px;
    font: inherit;
    background: var(--global-bg-color, #fff);
    color: var(--global-text-color, inherit);
  }

  .cv-modal__field textarea {
    resize: vertical;
    min-height: 70px;
  }

  .cv-modal__actions {
    display: flex;
    gap: 8px;
    justify-content: flex-end;
    margin-top: 6px;
  }

  .cv-modal__close {
    border: 1px solid #cbd5e1;
    background: transparent;
    color: inherit;
    border-radius: 8px;
    padding: 8px 12px;
    cursor: pointer;
    font-weight: 600;
  }

  .cv-modal__submit {
    border: 0;
    border-radius: 8px;
    padding: 8px 12px;
    background: #005e7a;
    color: #fff;
    cursor: pointer;
    font-weight: 600;
  }

  @media (max-width: 768px) {
    .education-card {
      flex-wrap: wrap;
      gap: 10px;
    }
  }
  
  body.layout--archive h1.page__title,
  body.layout--single.page-home h1.page__title {
    color: #005E7A !important;
  }

    /* ===== NEWS TOGGLE BUTTON ===== */
  .news-toggle-btn {
    display: none;
    background: transparent;
    border: 1.5px solid #005E7A;
    color: #005E7A;
    padding: 7px 20px;
    border-radius: 999px;
    font-size: 0.82rem;
    font-weight: 700;
    cursor: pointer;
    letter-spacing: 0.4px;
    transition: background 0.2s, color 0.2s;
  }

  .news-toggle-btn:hover {
    background: #005E7A;
    color: #fff;
  }
</style>

<!-- ===== RECENT NEWS ===== -->
<h3 style="color:#005E7A;font-size:1.1rem;">Recent News</h3>

<div class="news-timeline">

  <div class="news-item">
    <div class="news-item__date">April 2026</div>
    <div class="news-item__text">
      Awarded the <strong>Canada Impact + Research Training Award</strong>; joining Queen’s University, Canada, as a Postdoctoral Fellow.
    </div>
  </div>

  <div class="news-item">
    <div class="news-item__date">March 2026</div>
    <div class="news-item__text">
      Paper on the seismic fragility of masonry infills considering in-plane and out-of-plane interaction accepted in the <strong>Journal of Building Engineering</strong>.
    </div>
  </div>

  <div class="news-item">
    <div class="news-item__date">June 2025</div>
    <div class="news-item__text">
      Presented a paper on <strong>out-of-plane cyclic testing of masonry infills</strong> at <strong>COMPDYN 2025</strong>, Rhodes Island, Greece.
    </div>
  </div>

  <div class="news-item">
    <div class="news-item__date">June 2025</div>
    <div class="news-item__text">
      Presented a paper on <strong>DIC-based damage assessment in large-scale testing</strong> at the <strong>Canadian Masonry Symposium 2025</strong>, Ottawa, Canada.
    </div>
  </div>

</div>

</div>

<div style="text-align:center;margin:-8px 0 22px;">
  <button id="newsToggleBtn" class="news-toggle-btn">Show more news ▾</button>
</div>

<h3 style="color:#005E7A;font-size:1.1rem;">Research Interests</h3>

<div class="about-card-grid">
  <div class="about-hover-card"><span class="card-icon">🏗️</span> Large-scale experimental testing</div>
  <div class="about-hover-card"><span class="card-icon">💻</span> Nonlinear structural modelling</div>
  <div class="about-hover-card"><span class="card-icon">🌍</span> Seismic hazard, risk, and vulnerability assessment</div>
  <div class="about-hover-card"><span class="card-icon">📈</span> Performance-based earthquake engineering</div>
  <div class="about-hover-card"><span class="card-icon">🛡️</span> Resilience-based seismic design</div>
  <div class="about-hover-card"><span class="card-icon">🧱</span> Non-structural elements</div>
  <div class="about-hover-card"><span class="card-icon">🌿</span> Energy efficiency and climate resilience</div>
</div>

  
  
<h3 style="color:#005E7A;font-size:1.1rem;">Education</h3>

<div class="about-hover-card education-card">
  <img src="/images/iitr_logo.png" alt="IIT Roorkee Logo" style="width:70px; height:70px;">
  <div style="flex:1;">
    <strong>Ph.D. in Structural and Earthquake Engineering</strong><br>
    Indian Institute of Technology Roorkee, India
  </div>
  <div style="font-weight:600; color:#005E7A ;">
    Jul 2018 – Mar 2025
  </div>
</div>

<div class="about-hover-card education-card">
  <img src="/images/nit_srinagar_logo.png" alt="NIT Srinagar Logo" style="width:70px; height:70px;">
  <div style="flex:1;">
    <strong>M.Tech. in Structural Engineering</strong><br>
    National Institute of Technology Srinagar, India
  </div>
  <div style="font-weight:600; color:#005E7A ;">
    Jul 2016 – Jul 2018
  </div>
</div>

<div class="about-hover-card education-card">
  <img src="/images/nit_srinagar_logo.png" alt="NIT Srinagar Logo" style="width:70px; height:70px;">
  <div style="flex:1;">
    <strong>B.Tech. in Civil Engineering</strong><br>
    National Institute of Technology Srinagar, India
  </div>
  <div style="font-weight:600; color:#005E7A ;">
    Jul 2012 – Jun 2016
  </div>
</div>

<div style="margin-top:28px; display:flex; gap:12px; flex-wrap:wrap;justify-content:center;">
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
    /* CV modal */
    const openBtn = document.getElementById('openCvModalBtn');
    const closeBtn = document.getElementById('closeCvModalBtn');
    const modal = document.getElementById('cvModal');
    const form = document.getElementById('cvDownloadForm');
    const cvPath = '/files/CV_Zeeshan.pdf';

    if (openBtn && closeBtn && modal && form) {
      const setModalState = function (isOpen) {
        modal.classList.toggle('is-open', isOpen);
        modal.setAttribute('aria-hidden', isOpen ? 'false' : 'true');
        document.body.style.overflow = isOpen ? 'hidden' : '';
      };

      openBtn.addEventListener('click', function () { setModalState(true); });
      closeBtn.addEventListener('click', function () { setModalState(false); });
      modal.addEventListener('click', function (e) { if (e.target === modal) setModalState(false); });
      form.addEventListener('submit', function (e) {
        e.preventDefault();
        if (!form.checkValidity()) { form.reportValidity(); return; }
        setModalState(false);
        window.open(cvPath, '_blank', 'noopener');
        form.reset();
      });
    }

    /* Animated counters */
    function animateCounter(el) {
      const target = parseInt(el.getAttribute('data-target'), 10);
      const duration = 1200;
      const step = target / (duration / 16);
      let current = 0;
      const timer = setInterval(function () {
        current += step;
        if (current >= target) {
          el.textContent = target + '+';
          clearInterval(timer);
        } else {
          el.textContent = Math.floor(current);
        }
      }, 16);
    }

    const counters = document.querySelectorAll('.stats-bar__number[data-target]');
    if ('IntersectionObserver' in window) {
      const obs = new IntersectionObserver(function (entries) {
        entries.forEach(function (entry) {
          if (entry.isIntersecting) {
            animateCounter(entry.target);
            obs.unobserve(entry.target);
          }
        });
      }, { threshold: 0.5 });
      counters.forEach(function (el) { obs.observe(el); });
    } else {
      counters.forEach(animateCounter);
    }
    /* News Show more / less toggle */
    var newsItems = document.querySelectorAll('.news-item');
    var newsBtn   = document.getElementById('newsToggleBtn');
    var SHOW      = 3;
    if (newsItems.length > SHOW && newsBtn) {
      newsBtn.style.display = 'inline-block';
      var expanded = false;
      newsItems.forEach(function (item, i) {
        if (i >= SHOW) item.style.display = 'none';
      });
      newsBtn.addEventListener('click', function () {
        expanded = !expanded;
        newsItems.forEach(function (item, i) {
          if (i >= SHOW) item.style.display = expanded ? '' : 'none';
        });
        newsBtn.textContent = expanded ? 'Show less ▴' : 'Show more news ▾';
      });
    }

  })();
</script>
