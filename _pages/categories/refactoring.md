---
layout: archive
permalink: refactoring/
title: "refactoring"
author_profile: true
---

{% assign posts = site.categories.refactoring %}
{% for post in posts %}
{% include archive-single.html type=entries_layout %}
{% endfor %}
