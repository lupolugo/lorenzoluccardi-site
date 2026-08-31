---
title: "Articoli di giornale"
layout: single
permalink: /articoli/
---
{% for item in site.articoli %}
### [{{ item.title }}]({{ item.url }})
{{ item.excerpt }}
{% endfor %}