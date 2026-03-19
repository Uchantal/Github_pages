---
layout: default
title: Home
---

# Chantal's Dev Portfolio & Blog

Hello! I'm Chantal — a passionate developer exploring the world of software, web development, and open source.

This site is built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

## What You'll Find Here

- **Blog** — My thoughts on tech, coding, and learning
- **Projects** — Things I've built and am proud of
- **About** — A little more about me
- **Contact** — How to reach me

## Recent Posts

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>

