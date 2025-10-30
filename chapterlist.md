---
layout: page
title: White-Winged Harpy
category: 'harpy'
tags: ['harpy1']
---

[White-Winged Harpy](https://ncode.syosetu.com/n7961jr/) is a web novel by Isora Matsuri. It takes place in the same universe as Izora's previous series Silent Witch. Although it is not necessary to read that beforehand, I recommend you do read it and its sequel, Silent Witch Gaiden, first to get the whole experience. You can read Silent Witch [here](https://papersurgery.wordpress.com/novel/silent-witch/) and Gaiden [here.](https://seeker142.github.io/SilentWitchGaiden/)

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
