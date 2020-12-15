---
layout: page
title: Notes
---

<ul>
  {% for post in site.categories.Notes %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>