---
layout: default
#title: ""
category: c
permalink: /categories/c/
nav_exclude: true
---

<h1>{{ page.category }}</h1>
<ul>
  {% assign posts = site.categories[page.category] %}
  {% for post in posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
<a href="/">Back to Home</a>
