---
layout: distill
title: IFP
permalink: /cp/ifp
description: physique fondamentale
importance: 2
category: 'enseignements transversaux'
---

|          |          |          |
| :------: | -------- | -------: |
{%- for entry in site.data.cp.ifp %}
| **{{entry.type}}** | <a href="{{ entry.url }}" target="_blank" rel="noopener noreferrer">{{entry.title}}</a> | {{entry.format}} ({{entry.pages}}, {{entry.size}}) |
{%- endfor %}
