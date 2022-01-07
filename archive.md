---
title: Archives
permalink: /archives
---

## Categories
{% for category in site.categories %}
- [{{ category[0] }}](/category/{{ category[0] }}) <sup>[{{ category[1].size }}]</sup>
{% endfor %}

----

## Tags

{% for tag in site.tags %}
- [{{ tag[0] }}](/tag/{{ tag[0] }}) <sup>[{{ tag[1].size }}]</sup>
{% endfor %}

## Years

{% for y in site.years reversed %}
- [{{y}}](/year/{{y}})
{% endfor %}
