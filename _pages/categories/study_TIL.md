---
title: "Today I Learned 📝"
layout: archive
permalink: categories/TIL
author_profile: true
---

{% assign posts = site.categories.TIL %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}