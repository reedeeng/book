---
layout: chapter
title: chapter one
collection: chapter-1
---

{% assign this-chapter = page.collection %}
{% for section in site.collections.this-chapter %}
<li>{{ section.title }}</li>
{% endfor %}
