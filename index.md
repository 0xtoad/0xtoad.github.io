---
title: Yet another sec blog
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post }}
    </li>
  {% endfor %}
</ul>
