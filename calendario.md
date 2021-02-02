---
layout: page
title: Calendario
description: Elenco delle attività per ciascuna settimana
nav_order: 2
has_children: true
---

# 🗓 Calendario

In questa pagina trovi un riepilogo delle date importanti del corso. Per tutti i dettagli sulle proposte della settimana puoi consultare la pagina relativa.

{% for module in site.modules %}
{{ module }}
<br>
<br>
{% endfor %}
