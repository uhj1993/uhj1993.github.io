---
layout: archive
permalink: etc/
title: "etc"
author_profile: true
sidebar:
  nav: "main-sidebar"
---

{% assign posts = site.categories.etc %}
{% for post in posts %}
{% include archive-single.html type=entries_layout %}
{% endfor %}
