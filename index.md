---
layout: page
title: 李维的日志
tagline: Supporting tagline
---
{% include JB/setup %}

Read [李维的github主页](http://liweilog.info)
    
## 日志

    python hello.py

## 文章列表

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



