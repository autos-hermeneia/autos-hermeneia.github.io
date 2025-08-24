---
layout: page
title: Library
permalink: /library/
---

<h2>Books</h2>
<ul>
{% for post in site.categories.books %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span></li>
{% endfor %}
</ul>

<h2>Films</h2>
<ul>
{% for post in site.categories.films %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span></li>
{% endfor %}
</ul>

<h2>Songs</h2>
<ul>
{% for post in site.categories.songs %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span></li>
{% endfor %}
</ul>

<h2>Words</h2>
<ul>
{% for post in site.categories.words %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span></li>
{% endfor %}
</ul>

