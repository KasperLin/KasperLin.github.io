---
layout: page
title: Notes
---

<ul>
  {% for post in site.categories.notes %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>