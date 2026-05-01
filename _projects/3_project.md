---
layout: page
title: Fairness-Aware Federated Graph Learning
description: Addressing fairness and bias in federated learning settings over graph-structured data.
img: assets/img/projects/FairWAG.png
importance: 3
category: research
---

**Venue:** EAAMO 2025

FairWAG addresses fairness challenges in federated graph learning, where multiple parties collaboratively train models without sharing raw data. This work proposes a weighted aggregation strategy that balances model performance with fairness across heterogeneous clients, ensuring that the globally aggregated model does not disproportionately disadvantage certain groups or subpopulations.

{% include figure.liquid loading="eager" path="assets/img/projects/FairWAG.png" alt="FairWAG framework overview" class="img-fluid rounded z-depth-1" %}

**Key contributions:**
- Fairness-aware aggregation strategies for federated graph neural networks
- Theoretical analysis of fairness-utility tradeoffs in federated settings
- Experiments on real-world social and citation networks
