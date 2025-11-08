---
layout: archive
title: "NEWS"
permalink: /news/
author_profile: true
---

{% include base_path %}

{% assign sorted_news = site.news | sort: "date" | reverse %}
{% for news in sorted_news %}
  {{ news.content }}
{% endfor %}
