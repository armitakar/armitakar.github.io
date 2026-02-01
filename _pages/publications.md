---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<b>For the most updated list of publications, please visit <u><a href="https://scholar.google.com/citations?user=1SMLap0AAAAJ&hl=en">my Google Scholar profile</a>.</u></b>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
