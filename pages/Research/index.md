---
title: Research
layout: default
---

# Research

{% for post in site.research %}
  - {{ post.date | date: '%B %Y' }} <span class="separator">~</span> [{{ post.title }}]({{ post.url }})
{% endfor %}
