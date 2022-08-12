---
title: "Flexible and efficient simulation-based inference for models of decision-making"
authors:
- Jan Boelts
- Jan-Matthis Lueckmann
- Richard Gao
- Jakob H Macke
date: "2022-07-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "eLife"
publication_short: ""

abstract: Inferring parameters of computational models that capture experimental data is a central task in cognitive neuroscience. Bayesian statistical inference methods usually require the ability to evaluate the likelihood of the model—however, for many models of interest in cognitive neuroscience, the associated likelihoods cannot be computed efficiently. Simulation-based inference (SBI) offers a solution to this problem by only requiring access to simulations produced by the model. Previously, Fengler et al. introduced Likelihood Approximation Networks (LAN, Fengler et al., 2021) which make it possible to apply SBI to models of decision-making, but require billions of simulations for training. Here, we provide a new SBI method that is substantially more simulation-efficient. Our approach, Mixed Neural Likelihood Estimation (MNLE), trains neural density estimators on model simulations to emulate the simulator, and is designed to capture both the continuous (e.g., reaction times) and discrete (choices) data of decision-making models. The likelihoods of the emulator can then be used to perform Bayesian parameter inference on experimental data using standard approximate inference methods like Markov Chain Monte Carlo sampling. We demonstrate MNLE on two variants of the drift-diffusion model (DDM) and show that it is substantially more efficient than LANs. MNLE achieves similar likelihood accuracy with six orders of magnitude fewer training simulations, and is significantly more accurate than LANs when both are trained with the same budget. This enables researchers to perform SBI on custom-tailored models of decision-making, leading to fast iteration of model design for scientific discovery.

# Summary. An optional shortened abstract.
summary: We propose a new method to perform simulation-based inference for mixed data e.g., with continuous and discrete data types, like they often occur in models of decision-making.

tags:
- Source Themes
featured: true

links:
- name: Website
  url: https://elifesciences.org/articles/77220
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
