---
title: "Whishlist"
layout: single
permalink: /whishlist/
---
{% for item in site.whishlist %}
### [{{ item.title }}]({{ item.url }})
{{ item.excerpt }}
{% endfor %}
