---
layout: archive
title: "Spectral geometry seminar"
permalink: /seminar/
author_profile: true
read_more: "disabled"
---


{% include base_path %}

## Upcoming : 
{% assign sems = site.seminar | sort: 'date' | reverse %}
{% for post in sems limit:2 %}
  {% include archive-single.html %}
{% endfor %}

## Archive

