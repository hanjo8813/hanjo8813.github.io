---
title: "프로그래머스 사이트의 문제를 리뷰합니다."
layout: archive
permalink: categories/programmers    # url 이름 설정
author_profile: true
paginate: 10
---

{% assign posts = site.categories.Programmers %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}