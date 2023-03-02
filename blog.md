---
layout: page
title: Blog Posts
---

<section class="resume-section">
  <div class="resume-section-content">
    <h1 class="mb-0">My <span class="text-primary">Blog</span> Posts</h1>
    <p>&nbsp;</p>
    {% for post in site.posts %}
    <h3><a href="{{ post.url | absolute_url }}">{{post.title}}</a></h3>
    <div class="subheading mb-5">{{post.excerpt}}</div>
    <a href="{{ post.url | absolute_url}}" class="btn btn-primary">Read More</a>
    <p>&nbsp;</p>
    {% endfor %}
  </div>
</section>