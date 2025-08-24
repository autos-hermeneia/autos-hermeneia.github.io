
---
layout: page
title: Journal
permalink: /journal/
---

<ul>
{% for post in site.categories.journal %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
  </li>
{% endfor %}
</ul>

<p class="post-meta">Create posts in <code>_posts</code> with <code>categories: journal</code>.</p>
