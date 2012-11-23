---
layout: page
title: 小石头
tagline: 亢奋的小二青
---
{% include JB/setup %}

## 最新文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 鸣谢列表

[Jekyll Bootstrap](http://github.com/plusjade/jekyll-bootstrap)

## 游客语录

<!-- Duoshuo Comment BEGIN -->
<div class="ds-thread"></div>
<script type="text/javascript">
var duoshuoQuery = {short_name:"craigtaylorme"};
(function() {
	var ds = document.createElement('script');
	ds.type = 'text/javascript';ds.async = true;
	ds.src = 'http://static.duoshuo.com/embed.js';
	ds.charset = 'UTF-8';
	(document.getElementsByTagName('head')[0] 
	|| document.getElementsByTagName('body')[0]).appendChild(ds);
})();
</script>
<!-- Duoshuo Comment END -->
