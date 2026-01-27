---
title: ""
permalink: /contact/
layout: single
---

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

    <form action="https://formspree.io/f/xeegvbvg" method="POST" class="contact-form">

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

      <!-- THANK YOU REDIRECT -->
      <input type="hidden" name="_next" value="https://zeeshanbhat.github.io/contact/thanks/">

      <button type="submit" class="btn-send">Send</button>
    </form>
  </div>

</div>
