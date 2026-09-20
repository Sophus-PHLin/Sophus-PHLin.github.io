---
layout: default
title: Home
---

<div class="home-intro">
  <h1>Sophus</h1>
  <p>FURTHER DOWN THE NEST.</p>
</div>

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
