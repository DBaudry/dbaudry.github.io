+++
title = "Towards instance-dependent regret optimality in Episodic MDPs with Posterior Sampling"
date = 2026-10-19
authors = ["Victor Boone", "Cyrille Kone", "Waris Radji", "Odalric-Ambrym Maillard", "Dorian Baudry"]
abstract = "We study regret minimization in finite-horizon episodic Markov Decision Processes (MDPs). While minimax-optimal algorithms are known, tractable approaches to instance-dependent optimality are still lacking. Motivated by this gap, we introduce $\\pi_0$-PSRL, a variant of PSRL that uses posterior samples to decide when exploration is needed, while following a fixed reference policy $\\pi_0$ during exploration episodes. This decouples the test for exploration, triggered when the sampled and empirical MDPs have different optimal policies, from the choice of the policy used to gather information. The resulting design addresses a limitation of standard PSRL, where the sampled optimal policy may not be the optimal choice for exploration. We prove instance-dependent regret bounds for $\\pi_0$-PSRL, identifying the logarithmic exploration cost induced by $\\pi_0$ and taking a step toward matching asymptotic lower bounds for episodic RL. Our proof techniques showcase a novel proof structure to derive problem-dependent regret bounds in episodic MDPs, and concentration results for Dirichlet random variables, that may be of independent interest."
url_pdf = "https://arxiv.org/pdf/2610.26029"
url_preprint = "https://arxiv.org/abs/2610.26029"
math = true
publication_types = ["1"]
publication = "Conference on Neural Information Processing Systems (NeurIPS 2026)"
publication_short = "[NeurIPS 2026](https://neurips.cc/virtual/2026/poster/153285)"
url_custom = [{name = "Conference", url = "https://neurips.cc/virtual/2026/poster/153285"}]
featured = false
+++
