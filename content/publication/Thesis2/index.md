
+++
title = "PhD Thesis: Non-parametric algorithms for Multi-Armed Bandits"
date = 2022-12-10T12:12:00+01:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dorian Baudry"]

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
publication_types = ["7"]

# Publication name and optional abbreviated version.
publication = "PhD Thesis"
publication_short = "[]"
publication_extra = "[]"

# Abstract and optional shortened version.
abstract = "A Multi-Armed Bandits (MAB) is a learning problem where an agent sequentially chooses an action among a given set of candidates, collects a reward, and implements a strategy in order to maximize her sum of reward. Motivated by a case study in agriculture, we tackle in this thesis several problems that are relevant towards real-world applications of MAB. The first central question that we considered in this thesis is about the assumptions made on the distributions of rewards. While in theory it is usually convenient to consider simple parametric assumptions (e.g gaussian distributions), the practitioner may have some difficulty to find the right model fitting their problem. For this reason, we analyze two families of nonparametric algorithms, in the sense that they do not require strong parametric assumptions on the distributions for their implementation. We show that these two approaches can achieve strong theoretical guarantees in the standard bandit setting, improving what should be known in advance by the learner compared with previous algorithms. Then, we analyze some extensions of these algorithms that make them more suitable for some real-world applications. A second focus of our work is to consider alternative performance metrics, that may be more suitable than the expected sum of rewards for the practitioner. We propose a risk-aware algorithm for a bandit problem where the learner wants to find a safe arm according to a risk metric: the Conditional-Value-at-Risk. We also propose efficient algorithms for a problem analogous to the limit case of this setting, known as Extreme Bandits. Finally, we also adapt some of our approaches for standard variant of MAB, including one with non-stationary rewards and one with feedback grouped into batches of observations."
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
url_pdf = "files/Thesis_Dorian_Baudry.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "files/THESIS.pdf"
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

