---
title: Analyzing mortality and its determinants among individuals with type 1 and type 2 diabetes
summary: STATS 601 final project, University of Michigan.
date: '2023-04-27'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
url_code: 'https://github.com/timwhite0/stats601_project'
url_pdf: 'https://github.com/timwhite0/stats601_project/blob/main/Project%20-%20Tim%20White.pdf'
url_slides: ''
url_video: ''
---

Diabetes mellitus has consistently ranked among the ten leading causes of death in the United States for the past several decades. Diabetes-related mortality is prevalent across a wide range of sociodemographic subpopulations, and many previous studies have attempted to identify the risk factors and comorbidities that contribute most heavily to this phenomenon. However, surprisingly little attention has been paid to the distinction between the type 1 and type 2 variants of the disease in the context of mortality. In this report, we fill this gap in the literature by using unsupervised and supervised statistical learning methods to analyze the mortality risk profiles of individuals with type 1 and type 2 diabetes. We apply a dimension reduction technique to multiple-cause-of-death mortality data from the Centers for Disease Control and Prevention to explore the latent sociodemographic and health profiles of individuals whose deaths were attributed to diabetes in 2021, and we train several classification models to differentiate between type 1 and type 2 diabetes as a cause of death based on these characteristics. Our results suggest that sophisticated classification methods are capable of achieving moderate accuracy in distinguishing deaths due to type 1 diabetes from those due to type 2 diabetes, with tree-based and optimization-based classifiers such as random forest, AdaBoost, and kernel SVM providing a better holistic performance than model-based classifiers such as naive Bayes, quadratic discriminant analysis, and penalized logistic regression. We find that age is the most useful predictor for this classification task, followed by other sociodemographic predictors such as education, marital status, race, place of death, and sex. These findings provide important insights that could potentially improve the ability of practitioners to assess mortality risk in patients with type 1 and type 2 diabetes.