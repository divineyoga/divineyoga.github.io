---
layout: archive
title: "Events"
permalink: /events/
author_profile: true
---

{% include base_path %}

{% for post in site.events %}
  {% include archive-single-talk.html %}
{% endfor %}

