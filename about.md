---
layout: page
title: About
permalink: /about/
---

Some information about us and this blog will be coming soon.

### Individual Blog Posts

{% assign items_grouped = site.posts | group_by: 'author' %}
  {% for group in items_grouped %}
    <h3>{{group.name}}</h3>
    {% for item in group.items %}
      <p>{{item.title}}</p>
    {% endfor %}
  {% endfor %}

- [Jonah's Blog Posts](https://jonahwithoutthewhale.com/jonah/)
- [Kelly's Blog Posts](https://jonahwithoutthewhale.com/kelly/)
- [Rebecca's Blog Posts](https://jonahwithoutthewhale.com/rebecca/)

### Contact Us

[contact@jonahwithoutthewhale.com](mailto:contact@jonahwithoutthewhale.com)
