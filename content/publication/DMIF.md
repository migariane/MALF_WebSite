
+++
title = "The Delta-Method and Influence Function in Medical Statistics: a Reproducible Tutorial."  
date = "2022-07-11"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Miguel Angel Luque-Fernandez"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Arxiv Stat"
publication_short = "In *Arxiv* 2022"

# Abstract and optional shortened version.
abstract = "Approximate statistical inference via determination of the asymptotic distribution of a statistic is routinely used for inference in applied medical statistics (e.g. to estimate the standard error of the marginal or conditional risk ratio). One method for variance estimation is the classical Delta-method but there is a knowledge gap as this method is not routinely included in training for applied medical statistics and its uses are not widely understood. Given that a smooth function of an asymptotically normal estimator is also asymptotically normally distributed, the Delta-method allows approximating the large-sample variance of a function of an estimator with known large-sample properties. In a more general setting, it is a technique for approximating the variance of a functional (i.e., an estimand) that takes a function as an input and applies another function to it (e.g. the expectation function). Specifically, we may approximate the variance of the function using the functional Delta-method based on the influence function (IF). The IF explores how a functional ϕ(θ) changes in response to small perturbations in the sample distribution of the estimator and allows computing the empirical standard error of the distribution of the functional. The ongoing development of new methods and techniques may pose a challenge for applied statisticians who are interested in mastering the application of these methods. In this tutorial, we review the use of the classical and functional Delta-method and their links to the IF from a practical perspective. We illustrate the methods using a cancer epidemiology example and we provide reproducible and commented code in R and Python using symbolic programming. The code can be accessed at https://github.com/migariane/DeltaMethodInfluenceFunction"  
# Featured image thumbnail (optional)
image_preview = "2.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
 projects = ["DMIF.md"]

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/2206.15310"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "2.png"`.
[header]
image = "headers/2.png"

+++
