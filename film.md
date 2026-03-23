---
layout: default
title: 观影记录
---

# 观影记录🎬

{% for post in site.categories.film %}
  - {{ post.date | date: "%Y-%m-%d" }}  
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
