---
title: Projects
layout: default
---
![ProfilePhoto](/images/TandemAccelerator.jpg){: .inline-img}

# Projects

{% for post in site.posts %}
  - {{ post.date | date: '%B %Y' }} <span class="separator">~</span> [{{ post.title }}]({{ post.url }})
{% endfor %}
