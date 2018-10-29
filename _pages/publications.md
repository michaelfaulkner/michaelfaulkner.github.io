---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Open-source versions of my publications and submissions are available on the [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F) and citation information is available on [Google Scholar](googlescholar).

{% if author.googlescholar %} You can also find my articles on my Google Scholar profile. {% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
