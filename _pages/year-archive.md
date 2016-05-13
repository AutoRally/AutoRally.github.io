---
layout: single
title: Posts
author_profile: true
permalink: /year-archive/

---

{% include base_path %}

{% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
{% endfor %}