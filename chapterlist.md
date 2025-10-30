---
layout: page
title: White-Winged Harpy
category: 'harpy'
tags: ['harpy1']
---

{% assign harpy_posts = site.categories.harpy | sort: "date" | reverse %}
{% if harpy_posts and harpy_posts.size > 0 %}
  <h3>{{ page.title }}</h3>
  <ul>
    {% for post in harpy_posts %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p>No posts in the 'harpy' category yet.</p>
{% endif %}
