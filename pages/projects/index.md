---
title: Projects
layout: default
---
![ProfilePhoto](/images/TandemAccelerator.jpg){: .inline-img}

# Projects

{% for post in site.posts %}
    {% unless post.categories contains 'research' %}
  - {{ post.date | date: '%B %Y' }} <span class="separator">~</span> [{{ post.title }}]({{ post.url }})
    {% endunless %}
{% endfor %}

