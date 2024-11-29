---
layout: default
#title: Hack!
date: 2024-11-28
---
Test home!

`markup code test`

```
markup code block test.
```
---
# Latest posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
