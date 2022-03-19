---
layout: archive
permalink: /refactoring/
title: "Refactoring"
---

{% assign posts = site.categories.refactoring %}
{% for post in posts %}
{% include custom-archive-single.html type=entries_layout %}
{% endfor %}
