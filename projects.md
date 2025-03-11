---
layout: page
title: projects
---

<h1>Projects</h1>

<ul>
  {% for projpost in site.categories.projects %}
    <li><a href="{{ projpost.url }}">{{ projpost.date | date: "%B %Y" }} - {{ projpost.title }}</a></li>
  {% endfor %}
</ul>
