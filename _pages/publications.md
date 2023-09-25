---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

To download a PDF of each paper, click on the "paper" link below the title.

To navigate to the online version, click on the title.

You can also find my articles on <a href="https://scholar.google.com/citations?user=sTuP35MAAAAJ&hl=en" target="_blank">my Google Scholar profile</a>.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
