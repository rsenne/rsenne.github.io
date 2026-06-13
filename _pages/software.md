---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

A core part of my Ph.D. is building open-source tools for analyzing neural and
behavioral data. Below are the packages I develop and maintain.

## StateSpaceDynamics.jl

A Julia library for fitting and analyzing state-space models. It provides
efficient implementations of a range of SSMs — including the canonical Gaussian
linear dynamical system (Kalman filter/smoother), the Poisson LDS, and hidden
Markov models — with a unified, hierarchical interface aimed at neural data.
The package is published in the
[Journal of Open Source Software](https://doi.org/10.21105/joss.08077){:target="_blank"},
and I'm actively extending it with the recurrent switching linear dynamical
system (rSLDS).

[Documentation](https://depasquale-lab.github.io/StateSpaceDynamics.jl/stable/){:target="_blank"} ·
[GitHub](https://github.com/depasquale-lab/StateSpaceDynamics.jl){:target="_blank"} ·
[Paper (JOSS)](https://doi.org/10.21105/joss.08077){:target="_blank"}

*Senne, R., Loschinskey, Z., Fourie, J., Loughridge, C., & DePasquale, B. D.
(2025). StateSpaceDynamics.jl: A Julia package for probabilistic state space
models (SSMs). Journal of Open Source Software, 10(115), 8077.*

## ParallelMCMC.jl

A Julia package that implements MCMC algorithms parallelized across the sequence
length via Newton's method, i.e., DEER.

[GitHub](https://github.com/rsenne/ParallelMCMC.jl){:target="_blank"}
