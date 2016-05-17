---
layout: archive
author_profile: true
permalink: /
header:
  image: autorally_platform_header.jpg
---

{% include base_path %}

The AutoRally platform is a high-performance testbed for advanced perception and control research. The robot, developed at Georgia Tech, is integrated with ROS and designed as a self contained system that requires no external sensing or computing. The robot is a robust, cost-effective, and safe platform that opens the space of agressive autonomous off-road driving to all researchers.

## {{ site.data.ui-text[site.locale].recent_posts }}

{% for post in paginator.posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}

{% include paginator.html %}