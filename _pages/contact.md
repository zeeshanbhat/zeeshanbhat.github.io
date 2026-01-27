---
title: "Contact"
permalink: /contact/
layout: single
---

<div class="contact-wrap">

  <div class="contact-card contact-left">
    <h2 class="contact-title">Get in touch</h2>
    <p class="contact-subtitle">Send a message using the form.</p>

    <div class="contact-meta">
      <div class="meta-row">
        <span class="meta-icon">✉️</span>
        <div class="meta-text">
          <div class="meta-label">Email</div>
          <div class="meta-value"><a href="mailto:zbhat@eq.iitr.ac.in">zbhat@eq.iitr.ac.in</a></div>
        </div>
      </div>
    </div>
  </div>

  <div class="contact-card contact-right">
    <h2 class="contact-title">Send a message</h2>

    <!-- STEP 4: Replace YOUR_FORM_ID -->
    <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
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
  </div>

</div>
