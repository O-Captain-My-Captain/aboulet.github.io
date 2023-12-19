---
layout: distill
title: éléments finis
permalink: /ci/a4fisa/éléments_finis
importance: 1
category: 'A4 FISA'
---

|          |          |          |
| :------: | -------- | -------: |
{%- for entry in site.data.ci.a4fisa.finite_elements %}
| **{{entry.type}}** | <a href="{{ entry.url }}" target="_blank" rel="noopener noreferrer">{{entry.title}}</a> | {{entry.format}} ({{entry.pages}}, {{entry.size}}) |
{%- endfor %}
