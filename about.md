---
layout: page
title: About
permalink: /about/
---

Some information about us and this blog will be coming soon.

### Individual Blog Posts

{% for author in site.authors %}
- <a href="{{ author.url }}">{{ author.title }}'s Blog Posts</a></li>
{% endfor %}

### Contact Us

[contact@jonahwithoutthewhale.com](mailto:contact@jonahwithoutthewhale.com)
