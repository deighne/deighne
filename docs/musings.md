---
layout: page
title: Musings
permalink: /musings/
---

Here's a place for some longer-form writing I might get up to.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>