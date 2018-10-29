---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Open-source versions of my publications and submissions are available on the [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F) and citation information is available on [Google Scholar](https://scholar.google.co.uk/citations?hl=en&user=uFW1iN4AAAAJ&view_op=list_works&gmla=AJsN-F6QhUFJ7kRjW_OCY-lAWaHwUqZKiaJFOcRdl7TIzHPpC-9kR-yPUpTDeWepq0-3l9LkdZRxGxE--IRrOF7msyldHypL8OqssQJnUtZSZh-aJPbKEEM).

{% if author.googlescholar %} You can also find my articles on my Google Scholar profile. {% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
