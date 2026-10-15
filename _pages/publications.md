---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: false
classes: wide
---

<div class="page-intro">
  <p class="eyebrow">Publications</p>
  <h1>Selected research across cosmology, inference, and AI reasoning.</h1>
  <p class="page-deck">For a complete and current citation record, visit my <a href="https://scholar.google.co.in/citations?user=Q42woU4AAAAJ&hl=en">Google Scholar profile</a>.</p>
</div>

{% include base_path %}

<div class="publication-list">
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</div>
