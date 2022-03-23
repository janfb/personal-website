---
title: Comparing neural simulations by neural density estimation
subtitle: ""
authors:
  - Jan Boelts
  - Jan-Matthis Lueckmann
  - Pedro J. Goncalves
  - Henning Sprekeler
  - Jakob H. Macke
author_notes:
  - Technical University of Munich
  - Technical University of Munich
  - Research Center Bonn
  - Technical University Berlin
  - Technical University of Munich
doi: 10.32470/CCN.2019.1291-0
publication_short: In CCN
abstract: A common problem in computational neuroscience is the comparison of
  competing models in the light of observed data. Bayesian model comparison
  provides a statistically sound framework for this comparison based on the
  evidence each model provides for the data. In practice, however, models are
  often defined through complex simulators so that methods relying on likelihood
  functions are not applicable. Previous approaches in the field of Approximate
  Bayesian Computation (ABC) rely on rejection sampling to circumvent the
  likelihood, but are typically computationally inefficient. We propose an
  efficient method to perform Bayesian model comparison for simulation-based
  models. Using recent advances in posterior density estimation, we train a
  mixture-density network to map features of the observed data to the parameters
  of the posterior over models. We show that the method performs accurately on
  two tractable example problems, and present an application to a use case
  scenario from computational neuroscience -- the comparison of ion channel
  models.
tags: []
projects:
  - Simulation-based model comparison
slides: ""
url_pdf: ""
publication_types:
  - "1"
image:
  caption: Simulated training dataset (top) and predicted posterior probabilities
    of the three models (bottom)
  focal_point: ""
  preview_only: false
  filename: screenshot-2022-03-23-at-20.32.08.png
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
publication: 2019 Conference on Cognitive Computational Neuroscience, 13-16
  September 2019, Berlin, Germany
featured: true
date: 2022-03-23T19:13:12.383Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
