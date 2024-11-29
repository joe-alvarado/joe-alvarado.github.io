---
layout: page
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
    {{ post.date }}
  {% endfor %}
</ul>
