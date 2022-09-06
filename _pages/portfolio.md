---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}
{% assign sorted_publications = site.publications | sort: 'order' %}
{% for post in sorted_publications %}
  {% include archive-single.html %}
{% endfor %}
