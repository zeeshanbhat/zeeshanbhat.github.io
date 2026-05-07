---
title: ""
permalink: /contact/
layout: archive
---

<style>
  /* ===== COLLAB NOTE ===== */
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

    /* ===== CONTACT LAYOUT ===== */
  .contact-wrap {
    display: grid;
    grid-template-columns: 1fr;
    gap: 20px;
    margin-top: 8px;
  }

  @media (min-width: 700px) {
    .contact-wrap {
      grid-template-columns: 1fr 1.6fr;
      align-items: start;
    }
  }

  .contact-card {
    background: var(--global-bg-color, #fff);
    border: 1px solid #E6EBF2;
    border-radius: 14px;
    padding: 24px 22px;
    box-shadow: 0 4px 16px rgba(31, 58, 95, 0.07);
  }

  .contact-title {
    margin: 0 0 12px;
    font-size: 1.05rem !important;
    font-weight: 700;
    color: #005E7A !important;
    border-bottom: 2px solid #E6EBF2;
    padding-bottom: 10px;
  }

  .contact-subtitle {
    font-size: 0.9rem;
    color: var(--global-text-color, #444);
    margin: 0 0 18px;
    line-height: 1.6;
  }

  .contact-meta {
    display: flex;
    flex-direction: column;
    gap: 14px;
  }

  .meta-row {
    display: flex;
    align-items: flex-start;
    gap: 12px;
  }

  .meta-icon {
    font-size: 1.25rem;
    line-height: 1.3;
    flex-shrink: 0;
  }

  .meta-label {
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 0.7px;
    text-transform: uppercase;
    color: #5F7FA3;
    margin-bottom: 2px;
  }

  .meta-value {
    font-size: 0.9rem;
    color: var(--global-text-color, #333);
  }

  .meta-value a {
    color: #005E7A;
    text-decoration: none;
  }

  .meta-value a:hover {
    text-decoration: underline;
  }

  /* ===== CONTACT FORM ===== */
  .contact-form {
    display: flex;
    flex-direction: column;
    gap: 14px;
  }

  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 14px;
  }

  .field {
    display: flex;
    flex-direction: column;
    gap: 5px;
  }

  .field label {
    font-size: 0.82rem;
    font-weight: 600;
    color: #5F7FA3;
    letter-spacing: 0.3px;
  }

  .field input,
  .field textarea {
    padding: 9px 11px;
    border: 1px solid #cbd5e1;
    border-radius: 8px;
    font: inherit;
    font-size: 0.93rem;
    background: var(--global-bg-color, #fff);
    color: var(--global-text-color, inherit);
    transition: border-color 0.18s ease, box-shadow 0.18s ease;
    width: 100%;
    box-sizing: border-box;
  }

  .field input:focus,
  .field textarea:focus {
    outline: none;
    border-color: #005E7A;
    box-shadow: 0 0 0 3px rgba(0, 94, 122, 0.1);
  }

  .field textarea {
    resize: vertical;
    min-height: 130px;
  }

  .btn-send {
    align-self: flex-end;
    background: #005E7A;
    color: #fff;
    border: none;
    border-radius: 8px;
    padding: 10px 24px;
    font-size: 0.95rem;
    font-weight: 700;
    cursor: pointer;
    transition: background 0.2s ease, transform 0.2s ease, box-shadow 0.2s ease;
  }

  .btn-send:hover {
    background: #00789b;
    transform: translateY(-2px);
    box-shadow: 0 6px 16px rgba(0, 94, 122, 0.28);
  }

  .hp {
    display: none !important;
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

