+++
title = "Optimizing the coalition gain in Online Auctions with Greedy Structured Bandits"
date = 2024-12-07

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dorian Baudry", "Hugo Richard", "Maria Cherifa", "Clément Calauzennes", "Vianney Perchet"]

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
publication = "Advances in [Neural Information Processing Systems](https://neurips.cc/Conferences/2024) 36 (NeurIPS 2024)"
publication_short = "[NeurIPS 2024](https://neurips.cc/Conferences/2024)"
publication_extra = "[]"

# Abstract and optional shortened version.
abstract = "Motivated by online display advertising, this work considers repeated second-price auctions, where agents sample their value from an unknown distribution with cumulative distribution function F. In each auction t, a decision-maker bound by limited observations selects nt agents from a coalition of N to compete for a prize with p other agents, aiming to maximize the cumulative reward of the coalition across all auctions. The problem is framed as an N-armed structured bandit, each number of player sent being an arm n, with expected reward r(n) fully characterized by F and p + n. We present two algorithms, Local-Greedy (LG) and Greedy-Grid (GG), both achieving constant problem-dependent regret. This relies on three key ingredients: 1. an estimator of r(n) from feedback collected from any arm k, 2. concentration bounds of these estimates for k within an estimation neighborhood of n and 3. the unimodality property of r under standard assumptions on F. Additionally, GG exhibits problem-independent guarantees on top of best problem-dependent guarantees. However, by avoiding to rely on confidence intervals, LG practically outperforms GG, as well as standard unimodal bandit algorithms such as OSUB or multi-armed bandit algorithms."
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
url_pdf = "https://openreview.net/pdf?id=B74mb0tEY6"
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

