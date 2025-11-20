---
layout: category
title: Medicina
permalink: /medicina/
category: medicina
description: Aquí encontrarás mis artículos relacionados con medicin.

---

{% for post in site.posts %}
  {% if post.categories contains "medicina" %}
  - [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
