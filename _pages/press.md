---
layout: single
title: "Recent Press"
permalink: /press/
author_profile: false

header:
  overlay_image: autorally_platform_header2.jpg

sidebar:
  nav: "about"

---

{% include base_path %}

<div class="grid__wrapper">
  {% for press in site.press %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>