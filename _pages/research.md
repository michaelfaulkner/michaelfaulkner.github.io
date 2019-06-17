---
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

My research focuses on the statistical physics of real and emergent electrolytes. One application of my work is superconductivity, which is a state in which the electrical resistance of certain materials becomes zero at low temperatures. Thin-film and layered type-II superconductors behave as emergent two-dimensional electrolytes, which we use to model the phase transition between the normal and superconducting states. I’m currently further developing [my model](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.155412) of the two-dimensional electrolyte to explain the large and correlated resistance fluctuations that were recently measured at the superconducting transition in lanthanum strontium copper oxide.

I also model real electrostatics in biological and soft-matter physics, which are key to understanding a broad range of physical phenomena from protein folding in biological cells to ionic fluids in battery technology. We recently designed an [event-chain Monte Carlo algorithm](https://aip.scitation.org/doi/10.1063/1.5036638) for simulating electrical interactions in an atomistic water model. This sampling method is based on piecewise deterministic Markov processes, which usually mix faster than the stochastic dynamics of standard Markov-chain Monte Carlo, and also achieve machine precision, unlike molecular-dynamics simulations. We therefore expect our algorithm to outperform other modern methods when applied to these electrically charged systems. We're currently working on this benchmarking study.

The above work straddles the boundary between statistical physics and Bayesian computation in statistics. I also collaborate with statisticians to [develop Markov-chain Monte Carlo algorithms](https://arxiv.org/abs/1706.02649) for computational data science, where applicable examples include climate systems, political polling, and large-scale clinical trials in medical research. Over the next few years, we aim to make further connections between the Bayesian and physical worlds to complement my work developing new computational methods for them both.