---
layout: default
title: Blog
permalink: /blog/
---

# Blog

Welcome to my blog! Here I write about my experiences with coding, learning, and building projects.

<ul>
  {% for post in site.posts %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong><br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
