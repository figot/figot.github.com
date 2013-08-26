---
layout: default
title: 静水流深 青春如画 渔樵阿飞
tagline: Supporting tagline
---

## Author Info

My own data:
    
    title : 渔樵阿飞
    
    author :
      name : 渔樵阿飞
      email : sufeifan829@gmail.com
      github : figot
      weibo : [阿飞_Hust](http://weibo.com/figo829)
	  douban : [渔樵阿飞](http://www.douban.com/people/55920934/)

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do



