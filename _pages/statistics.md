---
layout: archive
permalink: /statistics/
title: "Statistics concepts"
author_profile: true
---

 <ul>
  {% for post in site.posts %}
    {% if post.categories[0] == "Statistics" %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>