---
layout: distill
title: physique statistique
permalink: /ci/a4mtrx/physique_statistique
importance: 4
category: 'A4 MTRX'
---

|          |          |          |
| :------: | -------- | -------: |
{%- for entry in site.data.ci.a4mtrx.statistical_physics %}
| **{{entry.type}}** | <a href="{{ entry.url }}" target="_blank" rel="noopener noreferrer">{{entry.title}}</a> | {{entry.format}} ({{entry.pages}}, {{entry.size}}) |
{%- endfor %}