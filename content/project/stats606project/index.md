---
title: Efficient initialization of the EM algorithm for Gaussian mixture models
summary: STATS 606 final project, University of Michigan.
date: '2023-04-14'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:

url_code: 'https://github.com/timwhite0/stats606_project'
url_pdf: ''
url_slides: ''
url_video: ''
---

The expectation-maximization (EM) algorithm is a convenient method of maximum likelihood estimation for Gaussian mixture models, but it is not guaranteed to converge to the global maximum of the (log-)likelihood function for Gaussian mixtures of an arbitrary number of components. As such, the success of the algorithm often hinges on the initialization of the parameters $\boldsymbol{\pi}$, $\boldsymbol{\mu}$, and $\boldsymbol{\Sigma}$. Many different initialization strategies have been proposed in the literature — some are based on random initialization, others involve data-driven methods like singular value decomposition or K-means clustering, and a handful are highly sophisticated procedures that require considerable computational effort. Perhaps unsurprisingly, no single initialization scheme has been shown to consistently outperform the others across all Gaussian mixture model settings. In this report, we study a relatively general model setting with a moderate number of mixture components where the parameters $\boldsymbol{\pi}$, $\boldsymbol{\mu}$, and $\boldsymbol{\Sigma}$ are treated as unknown. We consider four computationally feasible initialization methods, and we use simulation to assess the impact of these methods on the performance of the EM algorithm. In our simulation studies, we directly quantify the accuracy of the initial parameter values and characterize the post-initialization convergence behavior of the EM algorithm, and in doing so we build on earlier studies that focused primarily on the accuracy of the final EM estimates. Our results demonstrate that data-driven initialization strategies like svdEM (which uses singular value decomposition) and kmEM (which uses K-means clustering) tend to be more accurate and efficient than random initialization schemes, and in many settings they provide a reasonable alternative to more sophisticated but computationally intensive techniques. However, all of these initialization strategies tend to struggle when there is substantial overlap between the mixture components, especially when the dimension of the data is high. The optimal strategy for initializing $\boldsymbol{\pi}$, $\boldsymbol{\mu}$, and $\boldsymbol{\Sigma}$ in this setting remains an open question.
