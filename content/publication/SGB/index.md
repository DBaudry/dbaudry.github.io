+++
title = "Does Stochastic Gradient really succeed for bandits?"
date = 2025-12-03

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dorian Baudry", "Emmeran Johnson", "Simon Vary", "Ciara Pike-Burke", "Patrick Rebeschini"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Advances in [Neural Information Processing Systems](https://neurips.cc/Conferences/2025) 37 (NeurIPS 2025)"
publication_short = "[NeurIPS 2025](https://neurips.cc/Conferences/2025)"
publication_extra = "[]"

# Abstract and optional shortened version.
abstract = "Recent works of Mei et al. (2023, 2024) have deepened the theoretical understanding of the Stochastic Gradient Bandit (SGB) policy, showing that using a constant learning rate guarantees asymptotic convergence to the optimal policy, and that sufficiently small learning rates can yield logarithmic regret. However, whether logarithmic regret holds beyond small learning rates remains unclear. In this work, we take a step towards characterizing the regret regimes of SGB as a function of its learning rate. For two--armed bandits, we identify a sharp threshold, scaling with the sub-optimality gap, below which SGB achieves logarithmic regret on all instances, and above which it can incur polynomial regret on some instances. This result highlights the necessity of knowing (or estimating)  the gap to ensure logarithmic regret with a constant learning rate. For general K-armed bandits, we further show the learning rate must scale inversely with K to avoid polynomial regret. We introduce novel techniques to derive regret upper bounds for SGB, laying the groundwork for future advances in the theory of gradient-based bandit algorithms."
# Is this a selected publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Source Themes"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "https://openreview.net/pdf?id=gL4muAFwsh"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

