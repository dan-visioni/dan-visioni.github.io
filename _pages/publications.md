---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

I list here all my main articles. For a complete list, please check <u><a href="{{https://scholar.google.it/citations?user=5d0T8UAAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
