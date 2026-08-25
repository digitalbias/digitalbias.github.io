---
layout: splash
sitemap: true
permalink: /contact/
title: "Book a free 30-minute call"
excerpt: "Bring the thing that’s eating your week. I’ll tell you honestly whether I can help."
author_profile: false
---

<div class="home-shell home-shell--solo">

  <section class="sb-hero sb-hero--contact">
    <div class="sb-hero-copy">
      <div class="sb-hero-eyebrow">Free 30-minute consultation</div>
      <h1>Let’s look at your bottleneck.</h1>
      <p class="sb-lead">You don’t need a polished brief. Bring the operational mess that’s costing you the most time, and we’ll figure out whether I’m the right help.</p>
    </div>
  </section>

  <section class="sb-booking">
    <div class="sb-card sb-booking-main">
      <div class="eyebrow">On the call</div>
      <h2>What 30 minutes covers</h2>
      <ul class="sb-success-list">
        <li>The bottleneck costing you the most time or energy right now</li>
        <li>Where you want the business in 12 months</li>
        <li>Whether fractional COO work is a fit—or if something else would serve you better</li>
        <li>What working together would look like: scope, timeline, investment</li>
      </ul>
      <p>No high-pressure sales. If I’m not the right fit, I’ll say so.</p>
    </div>

    <div class="sb-card sb-booking-action">
      <div class="eyebrow">Book a time</div>
      {% if site.scheduling_url and site.scheduling_url.size > 0 %}
      <h2>Pick a 30-minute slot</h2>
      <p>Opens my Google Calendar booking page. Choose a time that works, and you’ll get a confirmation as soon as you book.</p>
      <div class="home-actions">
        <a class="btn btn--primary" href="{{ site.scheduling_url }}" target="_blank" rel="noopener">Book a free 30-minute call</a>
      </div>
      <p class="sb-booking-email">Prefer email? Write <a href="mailto:david.c.mitchell@gmail.com">david.c.mitchell@gmail.com</a> or <a href="https://www.linkedin.com/in/digitalbias">message me on LinkedIn</a>.</p>
      {% else %}
      <h2>Email two times that work</h2>
      <p>Send me two windows that work this week and a sentence about what’s stuck. I typically reply within a day and we’ll lock a time.</p>
      <div class="home-actions">
        <a class="btn btn--primary" href="mailto:david.c.mitchell@gmail.com?subject=Free%2030-minute%20consultation&amp;body=Hi%20Dave%2C%0A%0AI'd%20like%20to%20book%20a%2030-minute%20call.%0A%0ATwo%20times%20that%20work%20for%20me%20this%20week%3A%0A-%20%0A-%20%0A%0AWhat%20I'm%20stuck%20on%3A%0A">Email two times that work</a>
        <a class="btn" href="https://www.linkedin.com/in/digitalbias">Message on LinkedIn</a>
      </div>
      <p class="sb-booking-email">Or write <a href="mailto:david.c.mitchell@gmail.com">david.c.mitchell@gmail.com</a> directly.</p>
      {% endif %}
    </div>
  </section>

  <section class="sb-card">
    <div class="eyebrow">Not ready to talk yet</div>
    <h2>Get a feel for how I think</h2>
    <ul>
      <li><a href="/fractional-coo/">Fractional COO consulting</a> — what it is and what you walk away with</li>
      <li><a href="/about/">About Dave</a> — the Conserva story and how I work</li>
      <li><a href="/blog/">The blog</a> — essays on operations, leadership, and systems</li>
      <li><a href="/mba_notebook/">MBA sketchnotes</a> — practical business frameworks in visual form</li>
    </ul>
  </section>

</div>
