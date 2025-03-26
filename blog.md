---
layout: default
title: Blog
permalink: /blog/
---

<h1>📝 My Blog</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p><small>{{ post.date | date: "%B %d, %Y" }} — {{ post.author }}</small></p>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
