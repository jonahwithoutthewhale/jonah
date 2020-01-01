---
layout: page
title: About
permalink: /about/
---

Some information about us and this blog will be coming soon.

### The Rest of the Tribe

TBD

### Individual Blog Posts

{% for author in site.authors %}
- <a href="{{ author.url }}">{{ author.name }}'s Blog Posts</a>
{% endfor %}

### Contact Us

[contact@jonahwithoutthewhale.com](mailto:contact@jonahwithoutthewhale.com)
