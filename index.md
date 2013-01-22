---
layout: page
title: 筒子们好!
tagline: Supporting tagline
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## 关于我

一名 `新时代青年` ，一个脱离了低级趣味的`码农`:
    
    title : My GitHub Blog 
    
    author :
      name : 王景
      email : whugintama@gmail.com
      github : whugintama
      weibo : weibo.com/injhostgin


    
##  文章列表


Here's a my "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

i think i need a girlfriend.

