---
title: Blog
layout: default
---

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>

  <p>{{ post.excerpt }}</p>
  <p><a href="">Read more...</a></p>
{% endfor %}



