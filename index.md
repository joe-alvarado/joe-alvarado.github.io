---
layout: page
---
<h2>Welcome Back!</h2>
Hi, I moved my site to [GitHub](https://github.com/joe-alvarado){:target="blank"}. Old site had too much going on. I also made it so the site appearance will change depending on your device's current light/dark mode setting. This has been a good learning experience.

`;)`

```
git clone https://github.com/joe-alvarado/joe-alvarado.github.io
```
---
# Latest posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.date | date: "%B %d, %Y"}}	
    </li>
  {% endfor %}
</ul>
