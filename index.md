---
layout: default
---

# Basic System
5 card major, Multicolor 2 Diamond with Muiderberg

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }}) 
{{ post.excerpt }}
{% endfor %}
