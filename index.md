---
layout: base
title: Home
---

# Basic System
5 card major, Multicolor 2 Diamond with Muiderberg

{% for convention in site.conventions %}
## [{{ convention.title }}]({{ convention.url }}) 
{{ convention.description }}
{% endfor %}
