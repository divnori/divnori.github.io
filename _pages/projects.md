---
layout: archive
title: "Project Portfolio"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Last updated: 05-01-2022

Click on each project title link to view a demo video, more detailed project information, and code if available.

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

