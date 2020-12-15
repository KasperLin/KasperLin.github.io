---
layout: page
title: Notes
---

<ul>
  {% for post in site.notes %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>