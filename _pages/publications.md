---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Last updated: 05-01-2022

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{[author.googlescholar}](https://scholar.google.com/citations?user=w8VEYa8AAAAJ&hl=en)}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
