---
layout: single
title: Musings
permalink: /musings/
description: Like posting, but with editing and more words. No cohesion.
---

Weird, mostly.

<ul class="post-list">
  {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
  {% for post in site.posts %}
  <li>
    <h3><a class="post-link" href="{{ post.url }}">
      {{ post.title | escape }}
      | {{post.date | date: date_format}}
    </a></h3><p>{{ post.excerpt }}</p>
  </li>
  {% endfor %}
</ul>