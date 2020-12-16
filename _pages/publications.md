---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here's a list of all the articles I've worked on as lead author (under <b>Main Publications</b>) and a few others that I contributed to (2, under <b>Other Publications</b>, wip). Go the the page related to each article to download (wip) or e-mail me if you're interested.
I have contributed to some more (26), so for a complete list, please check my <u><a href="https://scholar.google.it/citations?user=5d0T8UAAAAAJ&hl=en">Google Scholar profile</a>.</u>

{% include base_path %}

Main Publications
======
  <ol>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>

Other Publications
======
  <ol>{% for post in site.publicationsothers reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>
