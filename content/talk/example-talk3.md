+++
date = 2017-01-01T00:00:00  # Schedule page publish date.

title = "Paradoxical collider effect in the analysis of non-communicable disease epidemiological data: a reproducible illustration and web application ."
time_start = 2019-02-19
#time_end = 2030-06-01T15:00:00
abstract =  "Classical epidemiology has focused on the control of confounding, but it is only recently that epidemiologists have started to focus on the bias produced by colliders. A collider for a certain pair of variables (e.g. an outcome Y and an exposure A) is a third variable (C) that is caused by both. In a directed acyclic graph (DAG), a collider is the variable in the middle of an inverted fork (i.e. the variable C in A -> C <- Y). Controlling for, or conditioning an analysis on a collider (i.e. through stratification or regression) can introduce a spurious association between its causes. This potentially explains many paradoxical findings in the medical literature, where established risk factors for a particular outcome appear protective. We use an example from non-communicable disease epidemiology to contextualize and explain the effect of conditioning on a collider. We generate a dataset with 1000 observations, and run Monte-Carlo simulations to estimate the effect of 24-h dietary sodium intake on systolic blood pressure, controlling for age, which acts as a confounder, and 24-h urinary protein excretion, which acts as a collider. We illustrate how adding a collider to a regression model introduces bias. Thus, to prevent paradoxical associations, epidemiologists estimating causal effects should be wary of conditioning on colliders. We provide R code in easy-to-read boxes throughout the manuscript, and a GitHub repository [https://github.com/migariane/ColliderApp] for the reader to reproduce our example. We also provide an educational web application allowing real-time interaction to visualize the paradoxical effect of conditioning on a collider [http://watzilei.com/shiny/collider/]."
event = "XXVII annual meeting Spanish Society of Epidemiology (SEE), Oviedo, Spain."
event_url = "https://scholar.harvard.edu/malf/presentations/paradoxical-collider-effect-analysis-non-communicable-disease-epidemiological"
location = "Oviedo, Spain"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   projects = ["deep-learning"]

# Links (optional).
url_pdf = ""
url_slides = "https://scholar.harvard.edu/malf/presentations/paradoxical-collider-effect-analysis-non-communicable-disease-epidemiological"
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
