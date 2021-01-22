---
layout: home
title: Sito di supporto per il corso
nav_exclude: true
seo:
  type: Course
  name: LCL-Doors
---

## Learning Creative Learning

In questo sito troverai:

- gli [avvisi](announcements.md) con le avventure da affrontare
- un [calendario](calendario.md),
- informazioni sullo [staff](staff.md)

## Iniziamo!

{% if site.announcements %}
{{ site.announcements.last }}
[Avvisi](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}
