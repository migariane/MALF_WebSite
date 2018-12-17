+++
title = "Educational Note: Paradoxical collider effect in the analysis of non-communicable disease epidemiological data: a reproducible illustration and web application"
date = "2018-12-17"

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
publication = "International Journal of Epidemiology"
publication_short = "In *IJE*"

# Abstract and optional shortened version.
abstract = "Classical epidemiology has focused on the control of confounding, but it is only recently that epidemiologists have started to focus on the bias produced by colliders. A collider for a certain pair of variables (e.g. an outcome Y and an exposure A) is a third variable (C) that is caused by both. In a directed acyclic graph (DAG), a collider is the variable in the middle of an inverted fork (i.e. the variable C in A → C ← Y). Controlling for, or conditioning an analysis on a collider (i.e. through stratification or regression) can introduce a spurious association between its causes. This potentially explains many paradoxical findings in the medical literature, where established risk factors for a particular outcome appear protective. We use an example from non-communicable disease epidemiology to contextualize and explain the effect of conditioning on a collider. We generate a dataset with 1000 observations, and run Monte-Carlo simulations to estimate the effect of 24-h dietary sodium intake on systolic blood pressure, controlling for age, which acts as a confounder, and 24-h urinary protein excretion, which acts as a collider. We illustrate how adding a collider to a regression model introduces bias. Thus, to prevent paradoxical associations, epidemiologists estimating causal effects should be wary of conditioning on colliders. We provide R code in easy-to-read boxes throughout the manuscript, and a GitHub repository https://github.com/migariane/ColliderApp for the reader to reproduce our example. We also provide an educational web application allowing real-time interaction to visualize the paradoxical effect of conditioning on a collider http://watzilei.com/shiny/collider/"
# Featured image thumbnail (optional)
image_preview = "collider.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
 projects = ["Collider.md"]

# Links (optional).
url_pdf = ""
url_preprint = "https://academic.oup.com/ije/advance-article/doi/10.1093/ije/dyy275/5248195"
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
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "density.tif"`.
[header]
image = "headers/collider.png"

+++

