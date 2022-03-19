---
layout: archive
permalink: /retrospect/
title: "Retrospect"
---

{% assign posts = site.categories.retrospect %}
{% for post in posts %}
{% include custom-archive-single.html type=entries_layout %}
{% endfor %}
