---
layout: archive
title: "Project Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

Click on each project title link to view a demo video, more detailed project information, and code if available.

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
