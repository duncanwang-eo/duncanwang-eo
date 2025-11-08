---
layout: archive
title: "NEWS"
permalink: /news/
author_profile: true
---

{% include base_path %}

{% assign sorted_news = site.news | sort: "date" | reverse %}
{% for news in sorted_news %}
  <div class="news-item">
    {{ news.content }}
    <p><a href="{{ news.url | relative_url }}" class="btn btn--small">View detail →</a></p>
  </div>
  {% unless forloop.last %}<hr>{% endunless %}
{% endfor %}
