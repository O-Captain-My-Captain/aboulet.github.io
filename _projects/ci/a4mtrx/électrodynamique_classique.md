---
layout: distill
title: électrodynamique classique
permalink: /ci/a4mtrx/électrodynamique_classique
importance: 2
category: 'A4 MTRX'
---

|          |          |          |
| :------: | -------- | -------: |
{%- for entry in site.data.ci.a4mtrx.electrodynamics %}
| **{{entry.type}}** | <a href="{{ entry.url }}" target="_blank" rel="noopener noreferrer">{{entry.title}}</a> | {{entry.format}} ({{entry.pages}}, {{entry.size}}) |
{%- endfor %}
