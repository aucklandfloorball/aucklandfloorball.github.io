---
layout: page
title: "News"
---

{% for post in site.categories.news %}
  {{ post.date | date_to_string }} [{{ post.title }}]({{ post.url }})
{% endfor %}
