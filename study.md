
---
layout: page
title: Study
permalink: /study/
---

<ul>
{% for post in site.categories.study %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
  </li>
{% endfor %}
</ul>

<p class="post-meta">Create posts in <code>_posts</code> with <code>categories: study</code>.</p>
