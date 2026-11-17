---
title: 'Neural posterior estimation for inferring weak lensing shear'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dingrui Tao
  - Camille Avestruz
  - Jeffrey Regier
  - LSST Dark Energy Science Collaboration

date: '2026-07-10'
doi: 'https://doi.org/10.48550/arXiv.2607.09867'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: arXiv

abstract: The prevailing approach to inferring weak gravitational lensing shear from images involves detecting galaxies, estimating their ellipticities, and calibrating these estimates to correct for image noise, selection bias, and model misspecification. Characterizing the statistical model and assumptions underlying this pipeline is challenging, which makes it difficult to propagate uncertainty through its various stages. As an alternative, we propose to infer shear using neural posterior estimation (NPE), a type of simulation-based inference. We train a deep neural network to map a simulated multiband image to a variational distribution over the underlying shear field, thereby folding galaxy detection, deblending, measurement, and calibration into a single implicit inference step. Once trained, the network accounts for all features present in the simulated images, including potential sources of bias. In experiments on simulated constant-shear images with increasingly complex observational effects, NPE produces accurate and well-calibrated posterior approximations for both shear components in the presence of blended galaxies, spatially varying point spread functions, stars, and detector artifacts. These results demonstrate that NPE can be a viable shear estimation method in settings where all anticipated features and artifacts can be simulated, a requirement that will become increasingly feasible as simulation fidelity improves in the coming decades.

tags: [Observational cosmology, weak gravitational lensing, astronomy image processing, convolutional neural networks, astrostatistics techniques, Bayesian statistics]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:

url_pdf: 'https://arxiv.org/abs/2607.09867'
url_code: 'https://github.com/prob-ml/blissWL'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
