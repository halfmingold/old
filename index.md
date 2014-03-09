---
layout: page
title: 重新开始
tagline: on the road
---
{% include JB/setup %}

很多次的想重新开始，什么时候怎样才算是重新开始呢。
也许就是下一秒。

文章列表.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
