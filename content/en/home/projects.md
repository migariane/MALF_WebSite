+++
# Projects widget.
# This widget displays all projects from `content/project/`.
widget = "projects"
active = true
date = "2020-12-24"

title = "Projects"
subtitle = ""

# Order that this section will appear in.
weight = 50

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.

# To remove toolbar, delete/comment all instances of `[[filter]]` below.

[[filter]]
  name = "All"
  tag = "*"
  
[[filter]]
  name = "TMLE"
  tag = ".TMLE"

[[filter]]
  name = "cvAUROC"
  tag = ".cvauroc"

[[filter]]
  name = "ELMPCE"
  tag = ".elmpce"

[[filter]]
  name = "Collider"
  tag = ".collider"

[[filter]]
  name = "HETMOR"
  tag = ".hetmor"
  
[[filter]]
  name = "CCI"
  tag = ".cci"

[[filter]]
  name = "DMIF"
  tag = ".dmif" 

+++

