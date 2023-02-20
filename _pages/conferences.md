---
layout: archive
title: "Conferences and Bootcamps"
permalink: /conferences/
author_profile: true
---
{% include base_path %}

{% for post in site.conferences reversed %}
  {% include archive-single-conferences.html %}
{% endfor %}