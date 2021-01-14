---
layout: page
title: Avvisi
nav_exclude: true
description: A feed containing all of the class announcements.
---

# Avvisi


{% assign Avvisi = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
