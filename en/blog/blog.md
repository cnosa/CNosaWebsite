---
layout: default
title: Blog
permalink: en/blog/
lang: en
---

# Blog: Check out what I'm thinking now

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d/%m/%Y" }}  
  {{ post.excerpt | strip_html | truncatewords: 20 }}
{% endfor %}