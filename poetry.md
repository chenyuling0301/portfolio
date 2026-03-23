---
layout: default
title: 诗词摘抄
---

# 诗词摘抄 📜

这里是我整理的一些诗词与个人解读：

{% for post in site.categories.poetry %}
  - {{ post.date | date: "%Y-%m-%d" }}  
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
