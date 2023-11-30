---
layout: base
title: Home
---

# Basic System
5 card major, Multicolor 2 Diamond with Muiderberg

<br>

{% for convention in site.conventions %}
## [{{ convention.title }}]({{ convention.url }}) 
<!-- {{ convention.description }} -->
{% endfor %}

<br>

### WIP

<br>

{% for wip in site.wips %}              
{% if wip.category == "wip" %}          
## [{{ wip.title }}]({{ wip.url }}) 
{% endif %}
{% endfor %}  
