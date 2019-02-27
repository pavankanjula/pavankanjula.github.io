---
layout: archive
permalink: /data-analytics/
title: "Exploratory Data Analytics"
author_profile: true
header:
  image: "/images/Otherpic.jpg"
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