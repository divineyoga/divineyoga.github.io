---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

## Youtube Video Uploads:

<iframe width="1280" height="720" src="https://www.youtube.com/embed/ZkSexFlloSM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Photo Gallery

<iframe src="https://albumizr.com/a/Ps1h" scrolling="no" frameborder="0" allowfullscreen width="700" height="400"></iframe>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
