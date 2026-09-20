---
layout: default
title: Archive
permalink: /archive.html
---

# Archive

{% if site.posts.size > 0 %}
{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }} — [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% else %}
No posts yet.
{% endif %}
