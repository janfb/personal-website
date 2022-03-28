---
title: "Flexible and efficient simulation-based inference for models of decision-making"
authors:
- Jan Boelts
- Jan-Matthis Lueckmann
- Richard Gao
- Jakob H Macke
date: "2022-01-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "bioRxiv"
publication_short: ""

abstract: Identifying parameters of computational models that capture experimental data is a central task in cognitive neuroscience. Bayesian statistical inference aims to not only identify a single configuration of best-fitting parameters, but to recover all model parameters that are consistent with the data and prior knowledge. Statistical inference methods usually require the ability to evaluate the likelihood of the model—however, for many models of interest in cognitive neuroscience, the associated likelihoods cannot be computed efficiently. Simulation-based inference (SBI) offers a solution to this problem by only requiring access to simulations produced by the model. Here, we provide an efficient SBI method for models of decision-making. Our approach, Mixed Neural Likelihood Estimation (MNLE), trains neural density estimators on model simulations to emulate the simulator. The likelihoods of the emulator can then be used to perform Bayesian parameter inference on experimental data using standard approximate inference methods like Markov Chain Monte Carlo sampling. While most neural likelihood estimation methods target continuous data, MNLE works with mixed data types, as typically obtained in decision-making experiments (e.g., binary decisions and associated continuous reaction times). We demonstrate MNLE on two variants of the drift-diffusion model (DDM) and compare its performance to a recently proposed method for SBI on DDMs, called likelihood approximation networks (LAN, Fengler et al. 2021). We show that MNLE is substantially more efficient than LANs, requiring six orders of magnitudes fewer model simulations to achieve comparable likelihood accuracy and evaluation time while providing the same level of flexibility. We include an implementation of our algorithm in the user-friendly open-source package sbi.

# Summary. An optional shortened abstract.
summary: We propose a new method to perform simulation-based inference for mixed data e.g., with continuous and discrete data types, like they often occur in models of decision-making.

tags:
- Source Themes
featured: false

links:
- name: Website
  url: https://www.biorxiv.org/content/10.1101/2021.12.22.473472v2.abstract
url_pdf: https://www.biorxiv.org/content/10.1101/2021.12.22.473472v2.full.pdf
url_code: 'https://github.com/mackelab/mnle-for-ddms'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Training a neural likelihood estimator on simulated data to perform parameter inference.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
