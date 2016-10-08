---
layout: page
title: Posts
permalink: /posts/
feature-img: "img/farmmorning2.jpg"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
