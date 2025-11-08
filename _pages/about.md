---
permalink: /
title: "Welcome to Rusi Wang's homepage!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I was born in February 1999 in Shanghai, China. I obtained my B.Eng. degree from the [University of Electronic Science and Technology of China](https://en.wikipedia.org/wiki/University_of_Electronic_Science_and_Technology_of_China) (Project 985, QS-ranking #=519) in 2021 and my M.Sc.(Eng.) degree from [Tongji University](https://en.wikipedia.org/wiki/Tongji_University) (Project 985, QS-ranking #=177) in 2024. I am currently a Ph.D. student at [Urban Mobility Institute](http://umi.tongji.edu.cn/), Tongji University.

I have been supervised by [Professor Chi Xie](https://scholar.google.com/citations?hl=en&user=LQ3KKYQAAAAJ&view_op=list_works&sortby=pubdate) at Transport and Energy Systems Laboratory (TESLA) [[📍Location](https://www.google.com/maps/place/4801+Caoan+Hwy,+Jia+Ding+Qu,+Shang+Hai+Shi,+China,+201804/@31.2810611,121.2100163,19z/data=!3m1!4b1!4m6!3m5!1s0x35b25cd3667ad407:0xa0105b5da462cc70!8m2!3d31.28106!4d121.21066!16s%2Fg%2F11r8dwp7vp?hl=en&entry=ttu&g_ep=EgoyMDI1MTAyOS4xIKXMDSoASAFQAw%3D%3D)] since August 2024. I have completed a <em>pre-dissertation research</em> on subsidy reallocation in a containerized freight transportation network. My current research focuses on multimodal traffic assignment (incorporating car-hailing, ridesharing, carpooling, bus, etc.) and travel demand management (e.g., road pricing, tradable credit scheme, booking cum rationing) in a dynamic context.

**For collaboration inquiries, please feel free to email me directly.**

# NEWS

{% assign sorted_news = site.news | sort: "date" | reverse %}
{% for news in sorted_news limit:3 %}
  {{ news.content }}
{% endfor %}

[View all news →](https://rusiwang99.github.io/news/)
