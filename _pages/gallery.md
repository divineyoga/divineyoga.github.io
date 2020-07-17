---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

## YouTube video uploads:

<iframe width="1280" height="720" src="https://www.youtube.com/embed/ZkSexFlloSM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Photo gallery of my students:

<iframe src="https://albumizr.com/a/Ps1h" scrolling="no" frameborder="0" allowfullscreen width="700" height="400"></iframe>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
