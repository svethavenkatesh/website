+++
# Projects widget.
# This widget displays all projects from `content/project/`.
widget = "projects"
active = true
date = "2016-04-20T00:00:00"

title = "Research"
subtitle = ""

# Order that this section will appear in.
weight = 15

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
  name = "Bayesian Optimization"
  tag = ".bayesian"

[[filter]]
  name = "Health Analytics"
  tag = ".health"

[[filter]]
  name = "Computer Vision"
  tag = ".computer-vision"


+++

Our methods are grounded in statistical machine learning and pattern recognition. In our research, we ask the following questions:

* What are the models that we must construct to be computationally scalable in big-data problems?
* How do we enhance the expressiveness of such models, what are the representations and can we develop appropriate inference and learning?