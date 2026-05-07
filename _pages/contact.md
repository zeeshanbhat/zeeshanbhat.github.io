---
title: ""
permalink: /contact/
layout: archive
---

<style>
  .collab-note {
    margin: 0 0 16px;
    padding: 18px 20px;
    border-radius: 14px;
    border: 1px solid rgba(0, 0, 0, 0.08);
    background: #fff;
    box-shadow: 0 8px 22px rgba(0, 0, 0, 0.06);
  }

  .collab-note h3 {
    margin: 0 0 6px;
    color: #005E7A;
    font-size: 1.05rem;
  }

  .collab-note p {
    margin: 0;
    font-size: 0.94rem;
  }

  .collab-links {
    margin-top: 11px;
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
  }

  .collab-links a {
    display: inline-block;
    padding: 5px 10px;
    border-radius: 8px;
    text-decoration: none;
    font-size: 0.78rem;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    font-weight: 700;
    color: #005E7A;
    border: 1px solid rgba(0, 0, 0, 0.14);
    background: #f8fafe;
  }

  .collab-links a:hover {
    background: #eef3ff;
    border-color: rgba(0, 94, 122, 0.35);
  }

</style>

<div class="collab-note">
  <h3>Collaboration</h3>
  <p>If my work matches your interests, let’s keep in contact and collaborate.</p>
  <div class="collab-links">
    <a href="/research/">Research highlights</a>
    <a href="/publications/">Publications</a>
    <a href="/portfolio/">Projects</a>
  </div>
</div>

<div class="contact-wrap">

  <!-- LEFT: ADDRESS -->
  <div class="contact-card contact-left">
    <h2 class="contact-title">Address</h2>
    <p class="contact-subtitle">
      Dept. of Earthquake Engineering<br/>
      Indian Institute of Technology Roorkee<br/>
      Roorkee, Uttarakhand, India
    </p>

    <div class="contact-meta">
      <div class="meta-row">
        <span class="meta-icon">📍</span>
        <div class="meta-text">
          <div class="meta-label">Location</div>
          <div class="meta-value">IIT Roorkee, Uttarakhand, India</div>
        </div>
      </div>

      <div class="meta-row">
        <span class="meta-icon">✉️</span>
        <div class="meta-text">
          <div class="meta-label">Email</div>
          <div class="meta-value">
            <a href="mailto:zbhat@eq.iitr.ac.in">zbhat@eq.iitr.ac.in</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- RIGHT: FORM -->
  <div class="contact-card contact-right">
    <h2 class="contact-title">Send a message</h2>

    <form id="contactForm" action="https://formspree.io/f/xeegvbvg" method="POST" class="contact-form">

      <!-- Spam protection -->
      <input type="text" name="_gotcha" class="hp" tabindex="-1" autocomplete="off">

      <div class="grid">
        <div class="field">
          <label for="firstName">First name</label>
          <input id="firstName" name="first_name" type="text" required>
        </div>

        <div class="field">
          <label for="lastName">Last name</label>
          <input id="lastName" name="last_name" type="text" required>
        </div>
      </div>

      <div class="field">
        <label for="email">Email *</label>
        <input id="email" name="email" type="email" required>
      </div>

      <div class="field">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="6" required></textarea>
      </div>

      <input type="hidden" name="_subject" value="New message from your website">

      <button type="submit" class="btn-send">Send</button>
    </form>

    <script>
      (function () {
        const form = document.getElementById('contactForm');
        if (!form) return;

        form.addEventListener('submit', async function (e) {
          e.preventDefault();
          const data = new FormData(form);

          try {
            const res = await fetch(form.action, {
              method: 'POST',
              body: data,
              headers: { 'Accept': 'application/json' }
            });

            if (res.ok) {
              window.location.href = '/contact/thanks/';
            } else {
              alert('Sorry—something went wrong. Please try again, or email me directly.');
            }
          } catch (err) {
            alert('Network error. Please try again, or email me directly.');
          }
        });
      })();
    </script>

  </div>

</div>

