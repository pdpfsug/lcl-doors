---
layout: page
title: Avvisi
nav_exclude: false
description: A feed containing all of the class announcements.
---

# Avvisi


{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
