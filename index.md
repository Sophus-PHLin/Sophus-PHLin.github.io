---
layout: default
title: Home
---

# Sophus

FURTHER DOWN THE NEST.

## Writings

{% if site.posts.size > 0 %}
{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }} — [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% else %}
Notes will appear here.
{% endif %}
