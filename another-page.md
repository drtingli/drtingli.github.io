---
layout: default
title: Another page
description: This is just another page
---

## Welcome to another page

_yay_

[new post](./_posts/2019-11-25-test-page)

[A Jekyll post_url link]({% post_url 2019-11-25-test-page %})

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[back](./)
