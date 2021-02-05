---
layout: page
title: Calendario
description: Elenco delle attività per ciascuna settimana
nav_order: 3
has_toc: false
---

# 🗓 Calendario

In questa pagina trovi un riepilogo delle date importanti del corso. Per tutti i dettagli sulle proposte della settimana puoi consultare la pagina relativa.

{% for module in site.modules %}
{{ module }}
{% endfor %}
