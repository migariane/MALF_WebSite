+++
title = "Using longitudinal targeted maximum likelihood estimation in complex settings with dynamic interventions"
date = "2019-09-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Michael Schomaker, Miguel Angel Luque-Fernandez et al."]

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
publication = "Statistics in Medicine"
publication_short = "In *SIM*"

# Abstract and optional shortened version.
abstract = "Longitudinal targeted maximum likelihood estimation (LTMLE) has very rarely been used to estimate dynamic treatment effects in the context of time-dependent confounding affected by prior treatment when faced with long follow-up times, multiple time-varying confounders, and complex associational relationships simultaneously. Reasons for this include the potential computational burden, technical challenges, restricted modeling options for long follow-up times, and limited practical guidance in the literature. However, LTMLE has desirable asymptotic properties, ie, it is doubly robust, and can yield valid inference when used in conjunction with machine learning. It also has the advantage of easy-to-calculate analytic standard errors in contrast to the g-formula, which requires bootstrapping. We use a topical and sophisticated question from HIV treatment research to show that LTMLE can be used successfully in complex realistic settings, and we compare results to competing estimators. Our example illustrates the following practical challenges common to many epidemiological studies: (1) long follow-up time (30 months); (2) gradually declining sample size; (3) limited support for some intervention rules of interest; (4) a high-dimensional set of potential adjustment variables, increasing both the need and the challenge of integrating appropriate machine learning methods; and (5) consideration of collider bias. Our analyses, as well as simulations, shed new light on the application of LTMLE in complex and realistic settings: We show that (1) LTMLE can yield stable and good estimates, even when confronted with small samples and limited modeling options; (2) machine learning utilized with a small set of simple learners (if more complex ones cannot be fitted) can outperform a single, complex model, which is tailored to incorporate prior clinical knowledge; and (3) performance can vary considerably depending on interventions and their support in the data, and therefore critical quality checks should accompany every LTMLE analysis. We provide guidance for the practical application of LTMLE."

# Featured image thumbnail (optional)
image_preview = "ltmle.svg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
 projects = ["TMLE.md"]

# Links (optional).
url_pdf = ""
url_preprint = "https://onlinelibrary.wiley.com/doi/full/10.1002/sim.8340"
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
image = "headers/ltmle.svg"

+++

