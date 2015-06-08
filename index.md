---
layout: page
tagline: Supporting tagline
---
{% include JB/setup %}

Use the menu above or see all posts below.


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
