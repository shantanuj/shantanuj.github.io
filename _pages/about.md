---
permalink: /
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<h2> About me </h2>
Hello! I am a research engineer at A*STAR Singapore's [Social and Cognitive Computing Department](https://www.a-star.edu.sg/ihpc/ihpc-research-capabilities/social-cognitive-computing) working in the direction of cognitively-based AI. 

My research interest is in building AI models that can -- (i) reason with **human-level** capabilities in a **reliable** and **interpretable** manner and (ii) **continually learn or update** their world knowledge through experience and any additional task-level supervision.

At A*STAR, I have specifically been working on:
1. Developing a **commonsense knowledge resource** for machine reading applications (advised by [Kenneth Kwok](https://www.researchgate.net/profile/Kenneth-Kwok-2) and [Erik Cambria](https://dr.ntu.edu.sg/cris/rp/rp00927)).
2. **Functionally integrating relevant cognitive phenomena** to build more effective computer vision models for scene understanding tasks (advised by [Basura Fernando](https://basurafernando.github.io/) and [Cheston Tan](https://scholar.google.com/citations?user=Up0UYEYAAAAJ)).

My CV is available [here](/cv/).

<h2 style="clear: both;" id="papers">Selected Papers </h2>
<p>Please see <u><a href="https://scholar.google.com/citations?user=GmGNq2MAAAAJ&hl=en">my Google Scholar profile</a></u> for a complete list.</p>
{% for publication in site.data.publications.papers%}
  {% include publication-single.html %}
{% endfor %}






