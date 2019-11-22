---
layout: page
title: Jonah
permalink: /jonah/
---

Testing Jonah author grouping...

{% for post in site.categories.[page.category] %}
{% assign author = site.data.authors[post.author] %}
  {{ author.Jonah }}
  {% endfor %}
