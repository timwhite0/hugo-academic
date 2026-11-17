---
title: 'Neural posterior estimation for tomographic weak lensing mass mapping'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shreyas Chandrashekaran
  - Camille Avestruz
  - Jeffrey Regier
  - LSST Dark Energy Science Collaboration

date: '2026-09-07'
doi: 'https://doi.org/10.48550/arXiv.2609.07833'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: arXiv

abstract: Weak gravitational lensing shear and convergence trace the distribution of baryonic and dark matter across space, making them a powerful probe of cosmic structure. Inferring shear and convergence from images is a challenging inverse problem. The prevailing approach to this task estimates shear from weighted averages of galaxy ellipticities, calibrates these estimates to account for systematic biases, and transforms them to reconstruct convergence, a multistage procedure that requires substantial computational resources and meticulous handling of statistical uncertainties. As an alternative, we propose a probabilistic approach to field-level weak lensing inference in which we train a deep neural network to directly map a multiband image to a variational distribution over the underlying tomographic shear and convergence fields. This neural posterior estimation (NPE) procedure implicitly marginalizes over nuisance variables in the cosmological forward model and does not require evaluating the likelihood function. It is also amortized, so it enables rapid posterior inference for astronomical surveys once the neural network is trained. When evaluated on synthetic images from the LSST-DESC DC2 Simulated Sky Survey, NPE produces well-calibrated variational distributions for shear and convergence that are consistent with the ground truth. We describe how maps sampled from these variational distributions could be used in a subsequent simulation-based inference procedure to approximate the posterior distribution over cosmological parameters.

tags: [Observational cosmology, weak gravitational lensing, astronomy image processing, convolutional neural networks, astrostatistics techniques, Bayesian statistics]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:

url_pdf: 'https://arxiv.org/pdf/2609.07833'
url_code: 'https://github.com/prob-ml/blissWL'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
