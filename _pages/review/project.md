---
title: "토이 프로젝트를 끝내고 나면 적어보아요"
layout: archive
permalink: categories/project
author_profile: true
---

{% assign posts = site.categories.project %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}