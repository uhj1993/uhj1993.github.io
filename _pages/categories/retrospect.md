---
layout: archive
permalink: retrospect/
title: "retrospect"
author_profile: true
sidebar:
  nav: "main-sidebar"
---

{% assign posts = site.categories.retrospect %}
{% for post in posts %}
{% include archive-single.html type=entries_layout %}
{% endfor %}
