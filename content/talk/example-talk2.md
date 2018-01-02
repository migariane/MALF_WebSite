+++
date = 2017-01-01T00:00:00  # Schedule page publish date.

title = "Ensemble Learning Targeted Maximum Likelihood Estimation, at London."
time_start = 2017-10-15
#time_end = 2030-06-01T15:00:00
abstract =  "eltmle is a Stata program implementing the targeted maximum likelihood estimation for the ATE for a binary outcome and binary treatment. Future implementations will offer more general settings. eltmle includes the use of a Super Learner called from the SuperLearner package v.2.0-21 (Polley E., et al. 2011). The Super-Learner uses V-fold cross-validation (10-fold by default) to assess the performance of prediction regarding the potential outcomes and the propensity score as weighted averages of a set of machine learning algorithms. We used the default SuperLearner algorithms implemented in the base installation of the tmle-R package v.1.2.0-5 (Susan G. and Van der Laan M., 2017), which included the following: i) stepwise selection, ii) generalized linear modeling (glm), iii) a glm variant that included second order polynomials and two-by-two interactions of the main terms included in the model."
event = "Stata Users Group Meeting, London, UK"
event_url = "https://scholar.harvard.edu/malf/presentations"
location = "London, United Kingdom"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   projects = ["deep-learning"]

# Links (optional).
url_pdf = ""
url_slides = "https://scholar.harvard.edu/malf/presentations"
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/bubbles-wide.jpg"

+++

Embed your slides or video here using [shortcodes](https://sourcethemes.com/academic/post/writing-markdown-latex/). Further details can easily be added using *Markdown* and $\rm \LaTeX$ math code.
