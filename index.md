---
layout: page
title: RudiJvr.com
tagline: The online home of RudiJvr
description: Minimal tutorial on making a simple website with GitHub Pages
---
# Posts
<ul class="posts">
{% for post in site.posts limit: 20 %}
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>
