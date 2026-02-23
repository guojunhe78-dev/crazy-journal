---
layout: default
title: Crazy Journal
---

欢迎来到 Crazy Journal！  

文明发展绝对用不上的知识都在这里！

最新一期：
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
