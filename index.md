---
layout: default
title: 首页
---

## 📜 文章列表

<ul>
  {% for post in site.posts %}
    <li>
      <span style="color: #666; font-size: 0.9em;">{{ post.date | date: "%Y-%m-%d" }}</span>
      &raquo; 
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
