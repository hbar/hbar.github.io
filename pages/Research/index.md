---
title: Research
layout: default
---

# Research

{% for post in site.posts %}
    {% if post.categories contains 'research' %}
  - {{ post.date | date: '%B %Y' }} <span class="separator">~</span> [{{ post.title }}]({{ post.url }})
    {% endif %}
{% endfor %}
