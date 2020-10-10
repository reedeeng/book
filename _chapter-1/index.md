---
layout: chapter
title: chapter one
collection: chapter-1
---

{% for section in site.collections[page.collection] %}
<li>{{ section.title }}</li>
{% endfor %}
