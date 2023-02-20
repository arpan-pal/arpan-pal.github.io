---
layout: archive
title: "Conferences"
permalink: /conferences/
author_profile: true
---
{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single-conferences.html %}
{% endfor %}