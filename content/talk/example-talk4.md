+++
date = 2017-01-01T00:00:00  # Schedule page publish date.

title = "The Delta-Method and Influence Function in Medical Statistics: a Reproducible Tutorial."
time_start = 2022-05-27
#time_end = 2030-06-01T15:00:00
abstract = "Approximate statistical inference via determination of the asymptotic distribution of a statistic is routinely used for inference in applied medical statistics (e.g. to estimate the standard error of the marginal or conditional risk ratio). One method for variance estimation is the classical Delta-method but there is a knowledge gap as this method is not routinely included in training for applied medical statistics and its uses are not widely understood. Given that a smooth function of an asymptotically normal estimator is also asymptotically normally distributed, the Delta-method offers a formula to obtain the large-sample variance of a function of an estimator with known large-sample properties. In a more general setting, it is a technique for approximating the variance of a functional (i.e., an estimand) that takes a function as an input and applies another function to it (e.g. the expectation function). Specifically, we may approximate the distribution using the functional Delta-method based on the influence function (IF). The IF explores how a functional ϕ(θ) changes in response to small perturbations in the sample distribution of the estimator and allows to compute the empirical standard error of the distribution of the functional. The ongoing development of new methods and techniques may pose a challenge for applied statisticians who are interested in mastering the application of these methods. In this tutorial we review the use of the classical and functional Delta-method and their links to the IF from a practical perspective. We illustrate the methods using a cancer epidemiology example and we provide reproducible and commented code in R and Python using symbolic programming. The code can be accessed at [https://github.com/migariane/DeltaMethodInfluenceFunction]." 
event = "Internal ICON group seminar, LSHTM, London, UK." 
event_url = "https://scholar.harvard.edu/malf/presentations/delta-method-and-influence-function-medical-statistics-reproducible-tutorial"
location = "London (LSHTM), UK"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   projects = ["deep-learning"]

# Links (optional).
url_pdf = ""
url_slides = "https://scholar.harvard.edu/files/malf/files/fdm.pdf"
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
