---
layout: page
title: About
permalink: /about/
---

Some information about us and this blog will be coming soon.

### Individual Blog Posts

Testing author grouping...


- [Jonah's Blog Posts](https://jonahwithoutthewhale.com/jonah/)
- [Kelly's Blog Posts](https://jonahwithoutthewhale.com/kelly/)
- [Rebecca's Blog Posts](https://jonahwithoutthewhale.com/rebecca/)

  {% for author in site.authors %}
    - <a href="{{ author.url }}">{{ author.title }}'s Blog Posts</a></li>
  {% endfor %}
</ul>

### Contact Us

[contact@jonahwithoutthewhale.com](mailto:contact@jonahwithoutthewhale.com)
