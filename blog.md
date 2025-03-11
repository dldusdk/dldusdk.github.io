---
layout: page
title: my blog
---

<ul>
  {% for projpost in site.categories.personal %}
    <li><a href="{{ projpost.url }}">{{ projpost.date | date: "%B %Y" }} - {{ projpost.title }}</a></li>
  {% endfor %}
</ul>
