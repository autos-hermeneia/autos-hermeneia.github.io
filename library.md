---
layout: page
title: Library
permalink: /library/
---

<!-- 상단 카테고리 링크(앵커) -->
<h2 style="margin-bottom:0.2rem;"><a href="#books">Books</a></h2>
<h2 style="margin-bottom:0.2rem;"><a href="#films">Films</a></h2>
<h2 style="margin-bottom:0.2rem;"><a href="#songs">Songs</a></h2>
<h2 style="margin-bottom:1.5rem;"><a href="#words">Words</a></h2>

<hr/>

<!-- Books 섹션 -->
<h2 id="books">Books</h2>
<ul>
{% for post in site.categories.books %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-meta">({{ post.date | date: "%Y-%m-%d" }})</span>
  </li>
{% endfor %}
</ul>

<!-- Films 섹션 -->
<h2 id="films">Films</h2>
<ul>
{% for post in site.categories.films %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-meta">({{ post.date | date: "%Y-%m-%d" }})</span>
  </li>
{% endfor %}
</ul>

<!-- Songs 섹션 -->
<h2 id="songs">Songs</h2>
<ul>
{% for post in site.categories.songs %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-meta">({{ post.date | date: "%Y-%m-%d" }})</span>
  </li>
{% endfor %}
</ul>

<!-- Words 섹션 -->
<h2 id="words">Words</h2>
<ul>
{% for post in site.categories.words %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-meta">({{ post.date | date: "%Y-%m-%d" }})</span>
  </li>
{% endfor %}
</ul>
