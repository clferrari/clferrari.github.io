---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here's a list of my most relevant publications. You can also find an updated and complete list of all my publication in my [Scholar](https://scholar.google.it/citations?user=aael17YAAAAJ&hl=it) profile.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
