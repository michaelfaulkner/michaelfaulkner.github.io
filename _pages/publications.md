---
title: "Publications"
permalink: /publications/
author_profile: true
---

Open-source versions are available on the [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F) and citation information is available on [Google Scholar](https://scholar.google.co.uk/citations?hl=en&user=uFW1iN4AAAAJ&view_op=list_works&gmla=AJsN-F6QhUFJ7kRjW_OCY-lAWaHwUqZKiaJFOcRdl7TIzHPpC-9kR-yPUpTDeWepq0-3l9LkdZRxGxE--IRrOF7msyldHypL8OqssQJnUtZSZh-aJPbKEEM).

## [All-atom computations with irreversible Markov chains](http://doi.org/10.1063/1.5036638)

# Michael F. Faulkner, Liang Qin, Anthony C. Maggs and Werner Krauth

# J. Chem. Phys. 149, 064113 (2018) ([arXiv:1804.05795](https://arxiv.org/abs/1804.05795))

The event-chain Monte Carlo (ECMC) method is an irreversible Markov process based on the factorized Metropolis filter and the concept of lifted Markov chains. We extended ECMC to all-atom models of multi-particle interactions that include the long-ranged Coulomb potential. For a three-dimensional systems composed of charge-neutral molecules, the algorithmic complexity to advance N particles an O(1) distance is O(N log N). Our particle-particle ECMC method achieved this without the interpolating mesh required for the efficient implementation of other modern Coulomb algorithms. An event-driven, cell-veto-based implementation samples the equilibrium Boltzmann distribution using neither time-step approximations nor spatial cutoffs on the range of the interaction potentials. This opened up many prospects for ECMC in soft condensed-matter and biological physics.


<!---
{% if author.googlescholar %} You can also find my articles on my Google Scholar profile. {% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->