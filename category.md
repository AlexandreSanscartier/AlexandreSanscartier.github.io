---
layout: page
title: Categories
permalink: /category/
---

{% for category in site.categories %}
  <h3><a href="{{ site.baseurl }}/category/{{ category[0] }}">{{ category[0] }}</a></h3>
{% endfor %}