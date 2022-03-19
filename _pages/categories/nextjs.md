---
layout: archive
permalink: nextjs
title: "nextjs"
author_profile: true
---

{% assign posts = site.categories.nextjs %}
{% for post in posts %}
{% include archive-single.html type=entries_layout %}
{% endfor %}
