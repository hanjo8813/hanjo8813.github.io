---
title: "test"
layout: archive
permalink: categories/BOJ
author_profile: true
---

{% assign posts = site.categories.BOJ %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}