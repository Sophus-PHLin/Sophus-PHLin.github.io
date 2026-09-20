---
layout: default
title: Home
---

# Sophus

FURTHER DOWN THE NEST.

## 学术 / Academic

{% for post in site.categories.academic %}
- {{ post.date | date: "%Y-%m-%d" }} — [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

---

## 音乐 / Music

{% for post in site.categories.music %}
- {{ post.date | date: "%Y-%m-%d" }} — [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

---

## 随笔 / Notes

{% for post in site.categories.notes %}
- {{ post.date | date: "%Y-%m-%d" }} — [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
