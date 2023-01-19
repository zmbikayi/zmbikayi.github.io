---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

If you can't find a one of the papers, send me an email and I will be happy to share the PDF.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
