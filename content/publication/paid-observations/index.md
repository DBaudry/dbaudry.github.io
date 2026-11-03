+++
title = "Best-of-Both Worlds for linear contextual bandits with paid observations"
date = 2025-10-08
authors = ["Nathan Boyer", "Dorian Baudry", "Patrick Rebeschini"]
abstract = "We study linear contextual bandits with paid observations, where at each round the learner observes a context, selects an action, and may pay a fixed cost to observe feedback from a subset of arms. We propose two Follow-the-Regularized-Leader algorithms with Best-of-Both-Worlds guarantees. The first, Agg-SPB, extends the SPB-matching framework of Tsuchiya and Ito (2024) by aggregating context-dependent stability terms, achieving the characteristic $T^{2/3}$ adversarial regret rate and logarithmic dependence on $T$ in stochastic environments. The second, CE-SPB, combines arm-dependent observation probabilities with an entropy-adaptive learning rate inspired by Kuroki et al. (2024). It achieves an entropy-adaptive $\\widetilde{O}(T^{2/3})$ adversarial guarantee and polylogarithmic stochastic regret, while avoiding the minimum-context-mass dependence arising in the stochastic analysis of Agg-SPB. Both algorithms further extend to corrupted stochastic environments with explicit corruption-dependent guarantees. These results establish that logarithmic stochastic regret is compatible with the $T^{2/3}$ adversarial regime for linear contextual bandits with paid observations, while highlighting a tradeoff between sharper horizon dependence in stochastic settings and path-dependent matching without explicit minimum-context-mass dependence."
url_pdf = "https://arxiv.org/pdf/2510.07424"
url_preprint = "https://arxiv.org/abs/2510.07424"
math = true
lastmod = 2026-09-08
publication_types = ["3"]
publication = "Preprint"
publication_short = "Preprint"
featured = false
+++
