---
layout: archive
title: "Testimonials"
permalink: /testimonials/
author_profile: true
---
<br/>
I'll be glad if you could provide me feedback for my course. Please also mention the duration you attended my classes for.

<br/>
<div id="hyvor-talk-view"></div>
<script type="text/javascript">
    var HYVOR_TALK_WEBSITE = 1125; // DO NOT CHANGE THIS
    var HYVOR_TALK_CONFIG = {
        url: "https://divineyoga.github.io/testimonials/",
        id: "1125"
    };
</script>
<script async type="text/javascript" src="//talk.hyvor.com/web-api/embed"></script>

{% include base_path %}

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}

