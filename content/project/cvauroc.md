+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "cvAUROC"

# Project summary to display on homepage.
summary = "cvAUROC is a Stata program that implements k-fold cross-validation for the AUC for a binary outcome after fitting a logistic regression model. Evaluating the predictive performance (AUC) of a set of independent variables using all cases from the original analysis sample tends to result in an overly optimistic estimate of predictive performance. K-fold cross-validation can be used to generate a more realistic estimate of predictive performance."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "roc.jpg"

# Tags: can be used for filtering projects.
tags = ["cvauroc"]

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
image = "headers/roc.jpg"
caption = "Luque-Fernandez et al. Data-Adaptive Estimation for Double-Robust Methods in Population-Based Cancer Epidemiology. American Journal of Epidemiology. 2017."

+++

Receiver operating characteristic (ROC) analysis is used for comparing predictive models, both in model selection and model evaluation. This method is often applied in clinical medicine and social science to assess the tradeoff between model sensitivity and specificity. After fitting a binary logistic regression model with a set of independent variables, the predictive performance of this set of variables -as assessed by the area under the curve (AUC) from a ROC curve- must be estimated for a sample (the test sample) that is independent of the sample used to predict the dependent variable (the training sample). An important aspect of predictive modeling (regardless of model type) is the ability of a model to generalize to new cases. Evaluating the predictive performance (AUC) of a set of independent variables using all cases from the original analysis sample tends to result in an overly optimistic estimate of predictive performance. K-fold cross-validation can be used to generate a more realistic estimate of predictive performance. To assess this ability in situations in which the number of observations is not very large, cross-validation and bootstrap strategies are useful. cvAUROC implements is a Stata program that implements k-fold cross-validation for the AUC for a binary outcome after fitting a logistic regression model.   
1. https://ideas.repec.org/c/boc/bocode/s458324.html  
2. https://github.com/migariane/cvAUROC  