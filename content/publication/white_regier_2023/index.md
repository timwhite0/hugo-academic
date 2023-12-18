---
title: 'Sequential Monte Carlo for detecting and deblending objects in astronomical images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jeffrey Regier

date: '2023-12-15'
doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Workshop on Machine Learning and the Physical Sciences, NeurIPS 2023

abstract: Many of the objects imaged by the forthcoming generation of astronomical surveys will overlap visually. These objects are known as blends. Distinguishing and characterizing blended light sources is a challenging task, as there is inherent ambiguity in the type, position, and properties of each source. We propose SMC-Deblender, a novel approach to probabilistic astronomical cataloging based on sequential Monte Carlo (SMC). Given an image, SMC-Deblender evaluates catalogs with various source counts by partitioning the SMC particles into blocks. With this technique, we demonstrate that SMC can be a viable alternative to existing deblending methods based on Markov chain Monte Carlo and variational inference. In experiments with ambiguous synthetic images of crowded starfields, SMC-Deblender accurately detects and deblends sources, a task which proves infeasible for Source Extractor, a widely used non-probabilistic cataloging program.

tags: [sequential Monte Carlo, astronomical images, deblending]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:

url_pdf: 'https://ml4physicalsciences.github.io/2023/files/NeurIPS_ML4PS_2023_172.pdf'
url_code: 'https://github.com/timwhite0/smcdeblender'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
