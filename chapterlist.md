---
layout: page
title: White-Winged Harpy
category: 'harpy'
---

[White-Winged Harpy](https://ncode.syosetu.com/n7961jr/) is a web novel by Isora Matsuri. It takes place in the same universe as Izora's previous series Silent Witch. Although it is not necessary to read that beforehand, I recommend you do read it and its sequel, Silent Witch Gaiden, first to get the whole experience. You can read Silent Witch [here](https://papersurgery.wordpress.com/novel/silent-witch/) and Gaiden [here.](https://seeker142.github.io/SilentWitchGaiden/)

<h3>Summary</h3>

At the Wedge Tower, where any and all magical knowledge is gathered, the mages of the Empire collaborate and compete, and once every three years, they recruit new apprentice mages.

“I want to fly.”—Tia, a young girl who aspires to be a mage for that reason alone, challenges the Wedge Tower’s entrance examination.

This is a story of mages, and of monsters on the brink of extinction.


{% assign harpy1 = site.tags.harpy1 %}
{% if harpy1 and harpy1.size > 0 %}
  {% assign harpy1 = harpy1 | sort: "chapter" %}
  <h3>{{ "Volume 1: The Wedge Tower" }}</h3>
  <ul>
    {% for post in harpy1 %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p> </p>
{% endif %}

{% assign harpy2 = site.tags.harpy2 %}
{% if harpy2 and harpy2.size > 0 %}
  {% assign harpy2 = harpy2 | sort: "chapter" %}
  <h3>{{ "Volume 2: Daily Lives of a New Teacher and the Apprentice Mages" }}</h3>
  <ul>
    {% for post in harpy2 %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p> </p>
{% endif %}

{% assign harpy3 = site.tags.harpy3 %}
{% if harpy3 and harpy3.size > 0 %}
  {% assign harpy3 = harpy3 | sort: "chapter" %}
  <h3>{{ "Volume 3: The Fated Brothers" }}</h3>
  <ul>
    {% for post in harpy3 %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p> </p>
{% endif %}
