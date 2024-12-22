---
layout: single
author_profile: true
share: false
read_time: false
permalink: /blog/
title: Blog
header:
  overlay_image: /assets/images/bluestone.jpeg
  caption: "Photo credit: Jeff Mercier"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>