---
title: A resampling technique for massive data in settings of bootstrap inconsistency
summary: Undergraduate honors thesis, University of Minnesota - Twin Cities.
tags:
  - resampling
  - bootstrap
  - bag of little bootstraps
  - consistency
date: '2022-05-10'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:

url_code: ''
url_pdf: ''
url_slides: honors_thesis_slides.pdf
url_video: ''
---

As massive data sets become more and more prevalent across the sciences, there is a growing need for accurate and computationally efficient methods of estimator quality assessment that can be applied under a variety of data-generating conditions. The nonparametric bootstrap is a straightforward and accurate method for approximating the sampling distribution of an estimator, but it becomes computationally unwieldy for large samples. Kleiner et al.’s bag of little bootstraps (BLB) provides a computationally efficient alternative to the bootstrap, but it is not expected to perform well in settings where the bootstrap is inconsistent. In this paper, we introduce the bag of little m out of n bootstraps (BLmnB), a modification of the BLB that aims to extend the method’s applicability to cases of bootstrap inconsistency. We formalize the BLmnB algorithm and compare its performance against that of the bootstrap and the BLB in two well-documented settings of bootstrap failure. Our results indicate that while the BLmnB is capable of outperforming the other two methods in one of these settings, it performs no better than the BLB in the other. In both settings, we find that the approximation accuracy of the BLmnB is sensitive to the choice of the resample size m. While these findings suggest that the BLmnB is a promising alternative to the BLB in at least some data- generating scenarios, further investigation is necessary in order to develop the underlying theory of the method and study its accuracy and runtime in other settings of bootstrap inconsistency.
