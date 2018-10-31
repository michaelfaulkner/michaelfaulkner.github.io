---
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /publications
---

{% include base_path %}

All-atom computations with irreversible Markov chains
======
Michael F. Faulkner, Liang Qin, Anthony C. Maggs and Werner Krauth
<br/>
[J. Chem. Phys. 149, 064113 (2018)](http://doi.org/10.1063/1.5036638) ([arXiv:1804.05795](https://arxiv.org/abs/1804.05795))

The event-chain Monte Carlo (ECMC) method is an irreversible Markov process based on the factorized Metropolis filter and the concept of lifted Markov chains. We extended ECMC to all-atom models of multi-particle interactions that include the long-ranged Coulomb potential. For a three-dimensional systems composed of charge-neutral molecules, the algorithmic complexity to advance N particles an O(1) distance is O(N log N). Our particle-particle ECMC method achieved this without the interpolating mesh required for the efficient implementation of other modern Coulomb algorithms. An event-driven, cell-veto-based implementation samples the equilibrium Boltzmann distribution using neither time-step approximations nor spatial cutoffs on the range of the interaction potentials. This opened up many prospects for ECMC in soft condensed-matter and biological physics.


Kinetic-energy choice in Hamiltonian/hybrid Monte Carlo
======
Samuel Livingstone, Michael F. Faulkner and Gareth O. Roberts
<br/>
Under review ([arXiv:1706.02649](https://arxiv.org/abs/1706.02649))

We investigated how different choices of kinetic energy in Hamiltonian Monte Carlo affect algorithm performance. To this end, we introduced two quantities which can be easily evaluated, the composite gradient and the implicit noise. Results were established on integrator stability and geometric convergence, and we showed that choices of kinetic energy that result in heavy-tailed momentum distributions can exhibit an undesirable negligible-moves property. We outlined a general efficiency-robustness trade off, and discussed implementations which rely on approximate gradients. We showed that the standard choice of a Gaussian momentum distribution is not always optimal in terms of either robustness or efficiency.


An electric-field representation of the harmonic XY model
======
Michael F. Faulkner, Steven T. Bramwell and Peter C. W. Holdsworth
<br/>
[J. Phys.: Condens. Matter 29, 085402 (2017)]((http://doi.org/10.1088/1361-648X/aa523f)) ([arXiv:1610.06692](https://arxiv.org/abs/1610.06692))

The harmonic XY (HXY) model is a lattice phase (or spin) model in which the classical phases interact via a piecewise parabolic interaction. In this paper, we presented a theory of the HXY model as a phase-model analogue of the two-dimensional electrolyte of [Phys. Rev. B  91, 155412](http://doi.org/10.1103/PhysRevB.91.155412) (see below).  While the electrolyte is an excellent model for investigating the mechanics of the BKT transition, it is a less realistic model of superfluid and superconducting condensate films and layers than the HXY model as its charges cannot be described as vortices in a phase field. We used our theory to explain how the HXY model recreates the high-temperature specific heat of condensates, and why this is strikingly different from that of the electrolyte. We then mapped the topological sectors of the electrolyte to global HXY condensate-phase twists, which may explain the nonergodicity in the condensate-phase field measured in layered cuprates at the superconducting transition Paper accepted with zero revisions.


From quantum to thermal topological-sector fluctuations of strongly interacting bosons in a ring lattice
======
Tommaso Roscilde, Michael F. Faulkner, Steven T. Bramwell and Peter C. W. Holdsworth
<br/>
[New J. Phys. 18, 075003 (2016)](http://doi.org/10.1088/1367-2630/18/7/075003) ([arXiv:1602.06247](https://arxiv.org/abs/1602.06247))

We extended the idea of [topological-sector fluctuations](http://doi.org/10.1103/PhysRevB.91.155412) (see below) to quantum and thermal phase slips in a model of strongly interacting bosons in a ring lattice. This provided strong evidence for the phase-slip fluctuations approaching a jump (distinct from the BKT universal jump) at the superfluid - Mott insulator transition. This paper was submitted by invitation. It is a special issue article on strongly interacting quantum gases in one dimension.


Phase order in superfluid helium films
======
Steven T. Bramwell, Michael F. Faulkner, Peter C. W. Holdsworth and Andrea Taroni
<br/>
[EPL (Europhys. Lett.) 112, 56003 (2015)](http://doi.org/10.1209/0295-5075/112/56003) ([arXiv:1508.07773](https://arxiv.org/abs/1508.07773))

We devised a protocol by which to measure the effective magnetic XY critical exponent β = 3π^2 / 128 in superfluid helium-4 films. This elucidated and provided a platform for universal finite-size scaling in condensate films and layers. This is an experimental article. We dedicated it to the memory of our friend and colleague Maxime Clusel, with whom we had many stimulating discussions on related topics.

Topological-sector fluctuations and ergodicity breaking at the Berezinskii-Kosterlitz-Thouless transition
======
Michael F. Faulkner, Steven T. Bramwell and Peter C. W. Holdsworth
<br/>
[Phys. Rev. B 91, 155412 (2015)](http://doi.org/10.1103/PhysRevB.91.155412) ([1502.00815](https://arxiv.org/abs/1502.00815))

We found topological-sector fluctuations to be a signal of the high-temperature phase of the Berezinskii-Kosterlitz-Thouless transition in the two-dimensional electrolyte. Our framework augments the charge-interaction representation of Kosterlitz and Thouless to include topological sectors of the electric field, which reflect charges tracing closed paths around the torus. Topological-sector fluctuations are absent in the low-temperature phase, where charges are confined in neutral pairs.  This reflects a nonergodicity in the electric field. In contrast, topological-sector fluctuations are nonzero in the ergodic, high-temperature phase, where the charges are deconfined. Topological order is defined by the absence of topological-sector fluctuations. This nonergodicity was cited as a base explanation for the [nonergodic dynamics measured in layered cuprates](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.134503) at the superconducting transition. Paper accepted with zero revisions.

<!---
{% if author.googlescholar %} You can also find my articles on my Google Scholar profile. {% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->
