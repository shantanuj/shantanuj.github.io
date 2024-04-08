---
permalink: /
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<h2 style="margin-top:0;"> About me </h2>
Hello! I am a researcher at A*STAR Singapore's [Center for Frontier AI Research (CFAR)](https://www.a-star.edu.sg/cfar). 

Broadly, my research interests are at the intersection of computer vision, machine learning and cognitive science, with the goal of developing **more intelligent and reliable AI** that can **continually learn from real-world/embodied experiences** and that exhibits **human-like reasoning capabilities**. At A*STAR, I have specifically worked on designing more effective scene understanding and reasoning methods by combining insights from relevant cognitive phenomena with machine learning techniques.

My CV is available [here](/cv/).

<h2 style="clear: both;" id="papers">Selected Papers </h2>
<p>Please see <a href="https://scholar.google.com/citations?user=GmGNq2MAAAAJ&hl=en">my Google Scholar profile</a> for a complete list.</p>
{% for publication in site.data.publications.papers%}
  {% include publication-single.html %}
{% endfor %}
