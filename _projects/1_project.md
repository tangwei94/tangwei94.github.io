---
layout: page
title: Infinite projected entangled-pair states
description: Gauge, optimization, and preconditioning methods for two-dimensional tensor network states.
importance: 1
category: research
published: true
---

**Infinite projected entangled-pair states (iPEPS)** are now among the most important numerical methods for studying strongly interacting quantum lattice models in two dimensions. Our recent work focuses on improving their efficiency, stability, and scope of application.

One of the central bottlenecks in iPEPS simulations is the high computational cost of variational optimization. To mitigate this issue, we introduced a **preconditioning scheme** that incorporates the geometry of the iPEPS manifold to substantially accelerate convergence with negligible additional cost [1].

Another major challenge in iPEPS simulations is that approximate environment contractions break the exact variational principle, allowing the optimizer to exploit contraction errors and become unstable. We identified that the **gauge degrees of freedom** on the virtual indices play an important role in this instability by strongly affecting the accuracy of two-dimensional tensor network contractions [2]. Building on this insight, we developed a manifold-based **gauge-fixed optimization** scheme that maintains the iPEPS in the minimal canonical form and significantly improves optimization stability [3].

We have also extended the iPEPS framework to two-dimensional interacting systems in a uniform magnetic field, where conventional approaches require large magnetic unit cells. To bypass this limitation, we introduced a **gauge-covariant iPEPS** ansatz in which physical observables remain translation invariant and the magnetic flux per plaquette enters as a continuous parameter [4].

### References {#references-ipeps}

- **[1]** X.-Y. Zhang, Q. Yang, P. Corboz, J. Haegeman, and W. Tang, _Accelerating two-dimensional tensor network optimization by preconditioning_, [Physical Review B **113**, 125111 (2026)](https://doi.org/10.1103/h396-yc28).
- **[2]** W. Tang, F. Verstraete, and J. Haegeman, _Matrix product state fixed points of non-Hermitian transfer matrices_, [Physical Review B **111**, 035107 (2025)](https://doi.org/10.1103/PhysRevB.111.035107).
- **[3]** W. Tang, L. Vanderstraeten, and J. Haegeman, _Gauging the variational optimization of projected entangled-pair states_, [arXiv:2508.10822 (2025)](https://arxiv.org/abs/2508.10822).
- **[4]** W. Tang, G. Möller, F. Verstraete, and L. Vanderstraeten, _Gauge-covariant projected entangled paired states for interacting systems in a magnetic field_, [arXiv:2604.24574 (2026)](https://arxiv.org/abs/2604.24574).
