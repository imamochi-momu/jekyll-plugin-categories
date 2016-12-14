# jekyll-plugin-categories

カテゴリーに関連するプラグイン。

## インストール

`<Jekyll Dir>/plugins/categories.rb`を突っ込むだけ。

## 使い方

### カテゴリの一覧を取得

```
<h1 id="page-title">{{ page.title }}</h1>
<ul class="posts">
  {% for category in page.category_list %}
  {{ page.test.a }}
  <li><a href="/categories/{{ category.title }}">{{ category.title }}</a></li>
  {% endfor %}
</ul>
```

### タグ出力

```ruby
{% category_list %}
```
