---
permalink: /
title: "About me"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I'm a research engineer at A*STAR Singapore's [Social and Cognitive Computing Department](https://www.a-star.edu.sg/ihpc/ihpc-research-capabilities/social-cognitive-computing) working in the direction of cognitively-inspired AI. 

I'm interested in building AI models that can -- i) understand and reason on scenes or passages with human-level capabilities in a reliable and interpretable manner, and ii) continually learn or update their world knowledge through environmental experience and any further supervision. 

My CV is available [here](/cv/).

*Recent publications*

Please see <u><a href="https://scholar.google.com/citations?user=GmGNq2MAAAAJ&hl=en">my Google Scholar profile</a></u> for a complete and up-to-date list.
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}