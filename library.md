---
layout: page
title: Library
permalink: /library/
---

<a id="top"></a>

<!-- 상단 카테고리 메뉴 -->
<nav>
  <ul>
    <li><a href="#books">Books</a></li>
    <li><a href="#films">Films</a></li>
    <li><a href="#songs">Songs</a></li>
    <li><a href="#words">Words</a></li>
  </ul>
</nav>

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
<p><a href="#top">↑ Back to top</a></p>

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
<p><a href="#top">↑ Back to top</a></p>

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
<p><a href="#top">↑ Back to top</a></p>

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
<p><a href="#top">↑ Back to top</a></p>
