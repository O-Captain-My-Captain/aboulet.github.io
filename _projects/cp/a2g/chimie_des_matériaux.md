---
layout: distill
title: chimie des matériaux
permalink: /cp/a2g/chimie_des_matériaux
importance: 1
category: 'A2 G'
---

|          |          |          |
| :------: | -------- | -------: |
{%- for entry in site.data.cp.a2g.chemistry %}
| **{{entry.type}}** | <a href="{{ entry.url }}" target="_blank" rel="noopener noreferrer">{{entry.title}}</a> | {{entry.format}} ({{entry.pages}}, {{entry.size}}) |
{%- endfor %}

