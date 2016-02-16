---
layout: page
title: Posts
permalink: /posts/
feature-img: "img/sample_feature_img_2.png"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>