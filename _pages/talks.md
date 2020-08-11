---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

--- 
layout: archive 
title: "Talks" 
permalink: /talks/ 
author_profile: true 
--- 

Here's a list of the main conferences/workshops I was invited to give talks to.

{% include base_path %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
