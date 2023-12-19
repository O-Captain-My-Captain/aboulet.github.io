---
layout: distill
title: vieux pont
permalink: /ci/a3fisag/vieux_pont
importance: 1
category: 'A3 FISA G'
---

##### **rappels de thermodynamique**

|          |          |          |
| :------: | -------- | -------: |
{%- for entry in site.data.ci.a3fisag.thermodynamics %}
| **{{entry.type}}** | <a href="{{ entry.url }}" target="_blank" rel="noopener noreferrer">{{entry.title}}</a> | {{entry.format}} ({{entry.pages}}, {{entry.size}}) |
{%- endfor %}