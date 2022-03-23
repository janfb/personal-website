---
title: sbi: A toolkit for simulation-based inference
subtitle: ""
authors:
  - Alvaro Tejero-Cantero
  - Jan Boelts
  - Michael Deistler
  - Jan-Matthis Lueckmann
  - Conor Durkan
  - Pedro J Gon{\c{c}}alves
  - David S Greenberg
  - Jakob H Macke
author_notes:
  - Equal contribution
  - Equal contribution
  - Equal contribution
  - Equal contribution
  - Equal contribution

doi: 10.21105/joss.02505
publication_short: In JOSS
abstract: Scientists and engineers employ stochastic numerical simulators to model empirically observed phenomena. In contrast to purely statistical models, simulators express scientific principles that provide powerful inductive biases, improve generalization to new data or scenarios and allow for fewer, more interpretable and domain-relevant parameters. Despite these advantages, tuning a simulator’s parameters so that its outputs match data is challenging. Simulation-based inference (SBI) seeks to identify parameter sets that a) are compatible with prior knowledge and b) match empirical observations. Importantly, SBI does not seek to recover a single ‘best’ data-compatible parameter set, but rather to identify all high probability regions of parameter space that explain observed data, and thereby to quantify parameter uncertainty. In Bayesian terminology, SBI aims to retrieve the posterior distribution over the parameters of interest. In contrast to conventional Bayesian inference, SBI is also applicable when one can run model simulations, but no formula or algorithm exists for evaluating the probability of data given parameters, i.e. the likelihood.
We present sbi, a PyTorch-based package that implements SBI algorithms based on neu- ral networks. sbi facilitates inference on black-box simulators for practising scientists and engineers by providing a unified interface to state-of-the-art algorithms together with docu- mentation and tutorials.
tags: []
projects:
  - Simulation-based inference
slides: ""
url_pdf: ""
publication_types:
  - "1"
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
publication: 
featured: false
date: 2022-03-23T19:13:12.383Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
