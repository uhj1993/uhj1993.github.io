---
layout: archive
permalink: nextjs
title: "NextJs"
author_profile: true
---

{% assign posts = site.categories.nextjs %}
{% for post in posts %}
{% include custom-archive-single.html type=entries_layout %}
{% endfor %}
