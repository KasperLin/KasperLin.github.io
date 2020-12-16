---
layout: page
title: Blogs
---

<ul>
  {% for post in site.categories.blogs %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>