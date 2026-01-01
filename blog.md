---
layout: default
title: Blog
permalink: /blog/
---

## Blog

> Logs, notes, experiments, and thoughts on cybersecurity.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color:#888;"> — {{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>
