---
layout: chapter
title: chapter one
chapter: chapter-1
---

ello

{% for section in site.collections[page.chapter] %}
<li>{{ section.title }}</li>
{% endfor %}
