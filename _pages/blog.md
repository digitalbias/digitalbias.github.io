---
layout: single
sitemap: true
permalink: /blog/
title: "Blog"
excerpt: "Essays on operations, leadership, nerd culture, and fiction writing."
author_profile: false
redirect_from:
  - /year-archive/
---

<div class="blog-category-grid">

  <a class="blog-cat-card" href="/categories/#business-operations">
    <div class="blog-cat-eyebrow">Category</div>
    <h2>Business &amp; Operations</h2>
    <p>Systems, delegation, small business strategy, MBA frameworks, and lessons from running a franchise.</p>
  </a>

  <a class="blog-cat-card" href="/categories/#leadership-lessons">
    <div class="blog-cat-eyebrow">Category</div>
    <h2>Leadership &amp; Lessons</h2>
    <p>Team dynamics, personal leadership, coaching, career development, and the human side of running a business.</p>
  </a>

  <a class="blog-cat-card" href="/categories/#nerd-culture-gaming">
    <div class="blog-cat-eyebrow">Category</div>
    <h2>Nerd Culture &amp; Gaming</h2>
    <p>Leadership lessons drawn from Aikido, chess, tabletop RPGs, sci-fi, and the occasionally surprising wisdom of games.</p>
  </a>

  <a class="blog-cat-card" href="/categories/#writing-fiction">
    <div class="blog-cat-eyebrow">Category</div>
    <h2>Writing &amp; Fiction</h2>
    <p>Updates on novels in progress, the writing life, publishing experiments, and the MBA Essentials sketchnote project.</p>
  </a>

</div>

---

## All Posts

Browse the full archive below, or [view by year](/year-archive/).

<div class="home-posts" style="margin-top:1.25rem;">
{% for post in site.posts limit:12 %}
  <article class="home-post">
    <div class="home-post-meta">{{ post.date | date: "%b %d, %Y" }}</div>
    <h3><a class="home-card-link" href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    {% if post.excerpt %}
      <p>{{ post.excerpt | markdownify | strip_html | strip_newlines | truncate: 130 }}</p>
    {% endif %}
  </article>
{% endfor %}
</div>

<div style="margin-top:1.5rem;">
  <a class="btn" href="/year-archive/">View Full Archive</a>
</div>
