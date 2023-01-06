---
permalink: /
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<h2 style="margin-top:0;"> About me </h2>
Hello! I am a research engineer at A*STAR Singapore's [Social and Cognitive Computing Department](https://www.a-star.edu.sg/ihpc/ihpc-research-capabilities/social-cognitive-computing) working in the direction of cognitively-based AI. 

Broadly, my research motive is to contribute towards building **more intelligent and reliable AI with human-level reasoning and learning capabilities** by taking insights from cognitive science to design appropriate computational operations/blocks, training methods and learning resources. 

At A*STAR, I specifically work on:
1. Developing a **commonsense knowledge resource** for machine reading and language understanding tasks (with [Kenneth Kwok](https://www.researchgate.net/profile/Kenneth-Kwok-2) and [Erik Cambria](https://dr.ntu.edu.sg/cris/rp/rp00927)).
2. **Functionally integrating relevant cognitive phenomena** to build more effective computer vision techniques for scene understanding and reasoning tasks (with [Basura Fernando](https://basurafernando.github.io/) and [Cheston Tan](https://scholar.google.com/citations?user=Up0UYEYAAAAJ)).

My CV is available [here](/cv/).

<h2 style="clear: both;" id="papers">Selected Papers </h2>
<p>Please see <a href="https://scholar.google.com/citations?user=GmGNq2MAAAAJ&hl=en">my Google Scholar profile</a> for a complete list.</p>
{% for publication in site.data.publications.papers%}
  {% include publication-single.html %}
{% endfor %}
