---
title: skoog.dev - blog
header: skoog.dev
description: my little blog
permalink: /
layout: default
---

{% for post in site.posts %}
  <p><a href="{{ post.url }}">{{ post.title }}</a><br>
  {{ post.description }}<br>
  {{ post.date | date_to_string }}</p>
{% endfor %}