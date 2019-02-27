---
layout: archive
permalink: /data-analytics/
title: "Exploratory Data Analytics"
author_profile: true
---

<ul>
  {% for post in site.posts %}
    {% if post.categories[0] == "Data Analytics" %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>