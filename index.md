---
layout: page
title: Welcome to ThinkMassive.Org
tagline: Supporting tagline
---
{% include JB/setup %}

Links above to check out my projects, posts below (nothing here yet)...


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
