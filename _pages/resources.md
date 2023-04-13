---
layout: archive
permalink: /resources/
title: "Resources"
author_profile: true
---

Here you can find a list of useful resources:

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}