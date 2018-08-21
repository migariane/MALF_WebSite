+++
title = "Targeted Maximum Likelihood Estimation: A tutorial"
date = "2018-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Miguel Angel Luque-Fernandez", "Michael Schomaker", "Bernard Rachet", "Mireille Schnitzer"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "Statistics in Medicine, SIM."
publication_short = "In *SIM*"

# Abstract and optional shortened version.
abstract = "When estimating the average treatment effect for a binary outcome, methods that incorporate propensity scores, the G-formula, or Targeted Maximum Likelihood Estimation (TMLE) are preferred over naïve regression approaches which often lead misspecified models. Some methods require correct specification of the outcome model, whereas other methods require correct specification of the exposure model. Doubly-robust methods only require correct specification of one of these models. TMLE is a semi-parametric doubly-robust method that enhances correct model specification by allowing flexible estimation using non-parametric machine-learning methods and requires weaker assumptions than its competitors. We provide a step-by-step guided implementation of TMLE and illustrate it in a realistic scenario based on cancer epidemiology where assumptions about correct model specification and positivity (i.e., when a study participant had zero probability of receiving the treatment) are nearly violated. This article provides a concise and reproducible educational introduction to TMLE for a binary outcome and exposure. The reader should gain sufficient understanding of TMLE from this introductory tutorial to be able to apply the method in practice. Extensive R-code is provided in easy-to-read boxes throughout the article for replicability. Stata users will find a testing implementation of TMLE and additional material in the appendix and at the following GitHub repository: https://github.com/migariane/SIM-TMLE-tutorial"

# Featured image thumbnail (optional)
image_preview = "steps.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   projects = ["TMLE"]

# Links (optional).
url_pdf = ""
url_preprint = "https://github.com/migariane/SIM-TMLE-tutorial"
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
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "DAG.jpg"
caption = ""

+++

KEYWORDS: Causal Inference, Machine Learning, Observational Studies, Targeted Maximum Likelihood Estimation, Super Learner, Epidemiology, Statistics
