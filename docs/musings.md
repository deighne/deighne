---
layout: page
title: Musings
permalink: /musings/
description: Like posting, but with editing and more words. No cohesion.
---

A place for longer-than-a-post writing.

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3><p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
