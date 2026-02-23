---
layout: default
title: Crazy Journal
---

欢迎来到 Crazy Journal！  

这里将向你展示群众的智慧。

最新一期：
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
