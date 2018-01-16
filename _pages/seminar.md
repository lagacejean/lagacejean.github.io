---
layout: archive
title: "Spectral geometry seminar"
permalink: /seminar/
author_profile: true
read_more: "disabled"
---


{% include base_path %}

## Upcoming

{% for post in site.seminar reversed limit:1%}
  {% include archive-single.html %}
{% endfor %}
