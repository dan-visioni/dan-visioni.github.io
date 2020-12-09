---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here's a list of all the articles I've worked on as lead author (8). 
I have contributed to many more (26), so for a complete list, please check <u><a href="https://scholar.google.it/citations?user=5d0T8UAAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
