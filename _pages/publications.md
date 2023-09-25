---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* To navigate to the online version of the article, click on the title
* To download a PDF of each paper, click on the "paper" link below the title
* You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=sTuP35MAAAAJ&hl=en)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
