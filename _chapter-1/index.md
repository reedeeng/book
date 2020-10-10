---
layout: chapter
title: chapter one
uniq: chapter-1
---

ello

{% for section in site.collections[page.uniq] %}
<li>{{ section.title }}</li>
{% endfor %}
