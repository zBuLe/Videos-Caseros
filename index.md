---
layout: default
title: Home
---

<h1>Our Family Videos</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> (Filmed: {{ post.filmed_date }})
    </li>
  {% endfor %}
</ul>
