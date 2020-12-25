+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Tutorial: computational causal inference for applied researchers"

# Project summary to display on homepage.
summary = "In this tutorial the computational we show the implementation of different causal inference estimators from a historical perspective where different estimators were developed to overcome the limitations of the previous one. Furthermore, we also briefly introduce the potential outcomes framework, illustrate the use of different methods using an illustration from the health care setting, and most importantly, we provide reproducible and commented code in Stata, R and Python for researchers to apply in their own observational study. Available at https://arxiv.org/abs/2012.09920"  

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "1.png"

# Tags: can be used for filtering projects.
tags = ["cci"]

# Optional external URL for project (replaces project detail page).
external_link = "Available at https://arxiv.org/abs/2012.09920"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/1.png"
caption = "Available at https://arxiv.org/abs/2012.09920"

+++
The purpose of many health studies is to estimate the effect of an exposure on an outcome. It is not always ethical to assign an exposure to individuals in randomised controlled trials, instead observational data and appropriate study design must be used. There are major challenges with observational studies, one of which is confounding that can lead to biased estimates of the causal effects. Controlling for confounding is commonly performed by simple adjustment for measured confounders; although, often this is not enough. Recent advances in the field of causal inference have dealt with confounding by building on classical standardisation methods. However, these recent advances have progressed quickly with a relative paucity of computational-oriented applied tutorials contributing to some confusion in the use of these methods among applied researchers. In this tutorial, we show the computational implementation of different causal inference estimators from a historical perspective where different estimators were developed to overcome the limitations of the previous one. Furthermore, we also briefly introduce the potential outcomes framework, illustrate the use of different methods using an illustration from the health care setting, and most importantly, we provide reproducible and commented code in Stata, R and Python for researchers to apply in their own observational study. The code can be accessed at

https://github.com/migariane/TutorialCausalInferenceEstimators  

KEYWORDS: Causal Inference; Regression adjustment; G-methods; G-formula; Propensity score; Inverse probability weighting; Double-robust methods; Machine learning; Targeted maximum likelihood estimation; Epidemiology; Statistics; Tutorial  