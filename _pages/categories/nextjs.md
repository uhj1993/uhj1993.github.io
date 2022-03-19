---
layout: archive
permalink: /nextjs/
title: "NextJs"
---

{% assign posts = site.categories.nextjs %}
{% for post in posts %}
{% include custom-archive-single.html type=entries_layout %}
{% endfor %}
