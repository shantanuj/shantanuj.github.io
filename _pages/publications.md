---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
Please see <u><a href="https://scholar.google.com/citations?user=GmGNq2MAAAAJ&hl=en">my Google Scholar profile</a></u> for a complete and up-to-date list.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
