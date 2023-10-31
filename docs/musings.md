---
layout: page
title: Musings
permalink: /musings/
---

A place for longer-than-a-post writing.

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3><p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
