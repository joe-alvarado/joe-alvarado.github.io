---
layout: page
title: Blog
permalink: /blog/
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> {{ post.excerpt }}
      {{ post.date | date: "%B %d, %Y"}}	
    </li>
  {% endfor %}
</ul>
