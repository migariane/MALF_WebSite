+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Ensemble Learning for Model Prediction in Cancer Epidemiology"

# Project summary to display on homepage.
summary = "To improve model selection and prediction in cancer epidemiology data adaptive ensemble learning methods based on the Super Learner as a method for variable selection via cross-validation are suitable. To selection of the optimal regression algorithm among all weighted combinations of a set of candidate machine learning algorithms the ensemble learning method improves model accuracy and prediction."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "cv.jpg"

# Tags: can be used for filtering projects.
tags = ["elmpce"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/cv.jpg"
caption = "Adapted from Vaan der Iann and Sherri Rose. Targeted Learning: Causal Inference for Observational and Experimental Data. Springer. 2011."

+++
I am developing a cutting edge approach to evaluate and calibrate the performance of new and classic cancer comorbodity index such as the Charlson's comorbidity score. Using a logistic model impose stringent constraints on the association between the explanatory variables and risk of death. For instance, the main-term logistic regression typically relies on a linear and additive relationship between a pre-specified transformation of the mean outcome and its predictors. Given the complex relationship between cancer mortality and comorbidity, the predictive power might be low if an incorrect parametric model is used as opposed to a more flexible option. I am using Data adaptive ensemble learning methods based on the Super Learner as a method for variable selection via cross-validation to select the optimum regression algorithm among all weighted combinations of a set of candidate machine learning algorithms. I am using different machine learning algorithms (Generalized Linear Models, Regression Trees, Bayesian Additive Regression Trees, Gradient Boosting, Generalized Additive Models, Stepwise Regression, Bayesian GLM, Lasso regression, Ridge Regression, Random Forest, Polynomial Spline Regression, and Bagging Classifier Trees). Then using cross-validation techniques I split the data into the mutually exclusive and exhaustive blocks of roughly equal size. Each algorithm is then fitted with nine blocks (the training set) and used to predict mortality for patients in the remaining block (the validation set). Finally, I calculate the mean squared error (MSE) between predicted and recorded mortality outcome comparing classical methods for prediction, machine learning and ensemble learning techniques.
