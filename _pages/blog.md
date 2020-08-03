---
title: Blog
layout: default
nav: left
order: 4
---

{% assign sorted = site.posts | reverse %}
{% for post in sorted %}
  <a href="{{ post.url }}">
    {{ post.title }}
  </a>
{% endfor %}
