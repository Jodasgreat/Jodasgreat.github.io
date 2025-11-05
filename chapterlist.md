---
layout: page
title: White-Winged Harpy
category: 'harpy'
---

[White-Winged Harpy](https://ncode.syosetu.com/n7961jr/) is a web novel by Isora Matsuri. It takes place in the same universe as Izora's previous series Silent Witch. Although it is not necessary to read that beforehand, I recommend you do read it and its sequel, Silent Witch Gaiden, first to get the whole experience. You can read Silent Witch [here](https://papersurgery.wordpress.com/novel/silent-witch/) and Gaiden [here.](https://seeker142.github.io/SilentWitchGaiden/)

{% assign harpy1 = site.tags.harpy1 | sort: "chapter" %}
{% if harpy_posts and harpy_posts.size > 0 %}
  <h3>{{ Volume 1: The Wedge Tower }}</h3>
  <ul>
    {% for post in harpy1 %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p> </p>
{% endif %}
{% assign harpy2 = site.tags.harpy2 | sort: "chapter" %}
{% if harpy_posts and harpy_posts.size > 0 %}
  <h3>{{ Volume 2: Daily Lives of New Apprentice Mages }}</h3>
  <ul>
    {% for post in harpy2 %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p> </p>
{% endif %}
