---
layout: distill
title: mécanique
permalink: /cp/a1g/mécanique
importance: 4
category: 'A1 G'
---

|          |          |          |
| :------: | -------- | -------: |
{%- for entry in site.data.cp.a1g.mechanics %}
| **{{entry.type}}** | <a href="{{ entry.url }}" target="_blank" rel="noopener noreferrer">{{entry.title}}</a> | {{entry.format}} ({{entry.pages}}, {{entry.size}}) |
{%- endfor %}