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

Attempt #2...

  {% assign items_grouped = site.posts | group_by: 'author.Jonah' %}
  {% for group in items_grouped %}
    <h3>{{group.name}}</h3>
    {% for item in group.items %}
      <p>{{item.title}}</p>
    {% endfor %}
  {% endfor %}
