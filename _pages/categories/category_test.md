---
title: "테스트카테고리(소1)"
layout: archive
permalink: categories/test    # url 이름 설정
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.Test %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}