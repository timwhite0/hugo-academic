---
title: Forecasting the weather with deep learning
summary: STATS 604 project \#4, University of Michigan. With Jaylin Lowe and Gabriel Patron.
date: '2023-12-04'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:

url_code: 'https://github.com/gapatron/stats604_project04'
url_pdf: ''
url_slides: ''
url_video: ''
---

Weather prediction is a notoriously challenging task due to the uncertainty inherent in dynamic meteorological systems. It is not uncommon for short-term forecasts of temperature, precipitation, and other conditions to be off the mark — these errors are a nuisance for everyday human activity and can negatively impact sectors like aviation and tourism.  Weather forecasts have traditionally been made by using supercomputers to simulate massive physical systems based on complex meteorological equations. This approach is known as numerical weather prediction, and it has been the predominant forecasting method for decades.

In recent years, however, meteorologists, computer scientists, and statisticians have discovered that deep neural networks are a powerful tool for producing accurate weather forecasts. As a result, there has been a shift away from numerical weather prediction and toward models based on machine learning. Our focus in this report is on the latter — we train models to predict temperature and precipitation up to four days into the future for 21 cities throughout the United States. Specifically, we produce forecasts of the minimum, average, and maximum daily temperature in these cities, as well as whether it snowed and whether any precipitation occurred. We develop a transparent and reproducible workflow via Git and Docker — our models can be trained (and retrained, if desired) and run on a daily basis to make predictions for the next four days in each city.
