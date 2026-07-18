---
layout: default
title: Blog
permalink: /blog/
---

{% assign blog_cover = site.static_files | where: "path", "/assets/illustrations/blog-cover.png" | first %}

<div class="blog-hero">
  <div class="blog-hero-copy">
    <p class="eyebrow">Skeeters field notes</p>
    <h1>From the dugout</h1>
    <p class="blog-intro">Planning notes, team updates, and the ideas helping our players grow on and off the field.</p>
  </div>
  {% if blog_cover %}
    <div class="blog-hero-art">
      <img src="{{ "/assets/illustrations/blog-cover.png" | relative_url }}" alt="" aria-hidden="true">
    </div>
  {% endif %}
</div>

<section class="post-list" aria-label="Blog posts">
  {% for post in site.posts %}
    <article class="post-card">
      <p class="post-card-meta">
        <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %-d, %Y" }}</time>
        {% if post.status == "draft" %}<span class="status-pill">Draft</span>{% endif %}
      </p>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></h2>
      <p>{{ post.excerpt | strip_html | strip_newlines | truncate: 220 }}</p>
      <a class="read-more" href="{{ post.url | relative_url }}">Read post <span aria-hidden="true">→</span></a>
    </article>
  {% else %}
    <p class="empty-state">The first post is on its way. Check back soon!</p>
  {% endfor %}
</section>
