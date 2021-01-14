---
layout: page
title: Avvisi
description: A feed containing all of the class announcements.
---

# Avvisi


{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
