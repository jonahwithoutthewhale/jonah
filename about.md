---
layout: page
title: About
permalink: /about/
---

### The Primary Tribe
Some information about us and this blog will be coming soon. In the meantime, I am testing out the width of this page and how much space it takes to go to the next line.

### The Rest of the Tribe
![Mable](/images/mable.jpg) ![Tessa](/images/tessa.jpg)
![Mazie](/images/mazie.jpg) ![Tessa](/images/tessa.jpg)

### Individual Blog Posts

{% for author in site.authors %}
- <a href="{{ author.url }}">{{ author.name }}'s Blog Posts</a>
{% endfor %}

### Contact Us

[contact@jonahwithoutthewhale.com](mailto:contact@jonahwithoutthewhale.com)
