---
layout: default
title: 首页
---

<style>
.section {
  margin: 40px 0;
}
.card {
  border: 1px solid #eee;
  padding: 20px;
  border-radius: 10px;
  margin-bottom: 20px;
  transition: 0.2s;
}
.card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
</style>

## 📝 最新文章

{% for post in site.posts limit:5 %}
<div class="card">
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.date | date: "%Y-%m-%d" }}</p>
</div>
{% endfor %}


## 📬 联系我

- GitHub: https://github.com/Lic233
