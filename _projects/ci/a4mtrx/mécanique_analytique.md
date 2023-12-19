---
layout: distill
title: mécanique analytique
permalink: /ci/a4mtrx/mécanique_analytique
importance: 1
category: 'A4 MTRX'
---

|          |          |          |
| :------: | -------- | -------: |
{%- for entry in site.data.ci.a4mtrx.analytical_mechanics %}
| **{{entry.type}}** | <a href="{{ entry.url }}" target="_blank" rel="noopener noreferrer">{{entry.title}}</a> | {{entry.format}} ({{entry.pages}}, {{entry.size}}) |
{%- endfor %}
