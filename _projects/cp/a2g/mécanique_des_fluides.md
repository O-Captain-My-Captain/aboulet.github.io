---
layout: distill
title: mécanique des fluides
permalink: /cp/a2g/mécanique_des_fluides
importance: 2
category: 'A2 G'
---


##### **mécanique des fluides**

|          |          |          |
| :------: | -------- | -------: |
{%- for entry in site.data.cp.a2g.fluid_mechanics %}
| **{{entry.type}}** | <a href="{{ entry.url }}" target="_blank" rel="noopener noreferrer">{{entry.title}}</a> | {{entry.format}} ({{entry.pages}}, {{entry.size}}) |
{%- endfor %}

---

##### **thermodynamique**

|          |          |          |
| :------: | -------- | -------: |
{%- for entry in site.data.cp.a2g.thermodynamics %}
| **{{entry.type}}** | <a href="{{ entry.url }}" target="_blank" rel="noopener noreferrer">{{entry.title}}</a> | {{entry.format}} ({{entry.pages}}, {{entry.size}}) |
{%- endfor %}



