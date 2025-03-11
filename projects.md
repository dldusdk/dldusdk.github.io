---
layout: page
title: projects
---

{% for tag in site.categories.projects %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for projpost in tag[1] %}
      <li><a href="{{ projpost.url }}">{{ projpost.date | date: "%B %Y" }} - {{ projpost.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
