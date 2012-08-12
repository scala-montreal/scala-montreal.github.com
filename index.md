---
layout: page
title: Scala Montreal
---

{% for post in site.posts %}
  {{ post.content }}
  <hr />
{% endfor %}

{% include JB/setup %}