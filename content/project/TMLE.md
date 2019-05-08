+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Targeted Maximum Likelihood Estimation: A Tutorial for Applied Researchers"

# Project summary to display on homepage.
summary = "TMLE is a semiparametric doubly-robust method for **Causal Infernece** that enhances correct model specification by allowing flexible estimation using non-parametric machine-learning methods and requires weaker assumptions than its competitors."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "steps.png"

# Tags: can be used for filtering projects.
tags = ["TMLE"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/steps.png"
caption = "Adapted from Vaan der Lann and Sherri Rose. Targeted Learning: Causal Inference for Observational and Experimental Data. Springer. 2011."

+++
When estimating the average treatment effect for a binary or continuous outcome, methods that incorporate propensity scores, the G-formula, or Targeted Maximum Likelihood Estimation (TMLE) are preferred over naïve regression approaches which often lead misspecified models. Some methods require correct specification of the outcome model, whereas other methods require correct specification of the exposure model. Doubly-robust methods only require correct specification of one of these models. TMLE is a semiparametric doubly-robust method that enhances correct model specification by allowing flexible estimation using non-parametric machine-learning methods and requires weaker assumptions than its competitors. We provide a step-by-step guided implementation of TMLE and illustrate it in a realistic scenario based on cancer epidemiology where assumptions about correct model specification and positivity (i.e., when a study participant had zero probability of receiving the treatment) are nearly violated. This tutorial (https://github.com/migariane/MALF) provides a concise and reproducible educational introduction to TMLE for a binary outcome and exposure. The reader should gain sufficient understanding of TMLE from this introductory tutorial to be able to apply the method in practice. Extensive R-code is provided in easy-to-read boxes throughout the article for replicability. Stata users will find a testing implementation of TMLE and additional material in the appendix and at the following GitHub repository: https://github.com/migariane/SIM-TMLE-tutorial  
 	Alternatively, readers can visit the following link where I provide a little bit more informal but interactive and reproducible TMLE tutorial using Rmarkdown. Furthermore, readers will gain more insights regarding the derivation of the Wald type confidence intervals based on the Functional Delta Method: 
 	https://migariane.github.io/TMLE.nb.html 
 	