---
title: "프로젝트 트러블 슈팅 기록"
layout: archive
permalink: categories/project
author_profile: true
---

{% assign posts = site.categories.project %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}