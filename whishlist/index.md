---
title: "Wishlist"
layout: single
permalink: /wishlist/
---
{% for item in site.wishlist %}
### [{{ item.title }}]({{ item.url }})
{{ item.excerpt }}
{% endfor %}