+++
# Date this page was created.
date = "2022-07-11"

# Project title.
title = "The Delta-Method and Influence Function in Medical Statistics: a Reproducible Tutorial."

# Project summary to display on homepage.
summary = "Approximate statistical inference via determination of the asymptotic distribution of a statistic is routinely used for inference in applied medical statistics (e.g. to estimate the standard error of the marginal or conditional risk ratio). One method for variance estimation is the classical Delta-method but there is a knowledge gap as this method is not routinely included in training for applied medical statistics and its uses are not widely understood."    

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "2.png"

# Tags: can be used for filtering projects.
tags = ["DMIF"]

# Optional external URL for project (replaces project detail page).
external_link = "Available at https://arxiv.org/abs/2206.15310"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/2.png"
caption = "Available at https://arxiv.org/abs/2206.15310"

+++
Given that a smooth function of an asymptotically normal estimator is also asymptotically normally distributed, the Delta-method allows approximating the large-sample variance of a function of an estimator with known large-sample properties. In a more general setting, it is a technique for approximating the variance of a functional (i.e., an estimand) that takes a function as an input and applies another function to it (e.g. the expectation function). Specifically, we may approximate the variance of the function using the functional Delta-method based on the influence function (IF). The IF explores how a functional ϕ(θ) changes in response to small perturbations in the sample distribution of the estimator and allows computing the empirical standard error of the distribution of the functional. The ongoing development of new methods and techniques may pose a challenge for applied statisticians who are interested in mastering the application of these methods. In this tutorial, we review the use of the classical and functional Delta-method and their links to the IF from a practical perspective. We illustrate the methods using a cancer epidemiology example and we provide reproducible and commented code in R and Python using symbolic programming. The code can be accessed at 

https://github.com/migariane/DeltaMethodInfluenceFunction     

KEYWORDS: Causal Inference; Statistical Inference; Influence Function; Delta Method; Epidemiology; Statistics; Tutorial  