<style>
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 20px;
}
.card {
  border: 1px solid #eee;
  padding: 20px;
  border-radius: 10px;
  transition: 0.2s;
}
.card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
</style>

## 📝 最新文章

<div class="cards">
{% raw %}
{% for post in site.posts %}
  <div class="card">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.date | date: "%Y-%m-%d" }}</p>
    <p>{{ post.excerpt | strip_html | truncate: 100 }}</p>
  </div>
{% endfor %}
{% endraw %}
</div>

## 📬 联系我

- GitHub: https://github.com/Lic233
