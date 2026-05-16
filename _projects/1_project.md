---
layout: page
title: Gauge-aware optimization for iPEPS
description: Stable and reliable variational optimization methods for two-dimensional tensor network states.
img: assets/img/12.jpg
importance: 1
category: research
published: true
---

Variational infinite projected entangled-pair states (iPEPS) are a central tool for strongly interacting quantum lattice models in two dimensions. A recurring issue in practical iPEPS calculations is that the same physical state can be represented in many different gauges, while approximate contraction algorithms and gradient-based optimization can be strongly affected by this gauge freedom.

My work has shown that fixed points of non-Hermitian transfer matrices provide useful diagnostics for tensor network environments and gauge choices [1]. Building on this, we developed a gauge-fixed variational optimization scheme for projected entangled-pair states, using manifold-optimization ideas to keep the tensors in a better-conditioned representation during optimization [2].

In related work, we demonstrated that local approximations to the tangent-space metric can be used as preconditioners for two-dimensional tensor network optimization, significantly accelerating convergence with little additional cost [3]. Together, these results point toward iPEPS algorithms that are more stable because they account for the geometry and gauge structure of the variational manifold.

## References

[1] W. Tang, F. Verstraete, and J. Haegeman, Matrix product state fixed points of non-Hermitian transfer matrices, *Physical Review B* **111**, 035107 (2025). [doi:10.1103/PhysRevB.111.035107](https://doi.org/10.1103/PhysRevB.111.035107)

[2] W. Tang, L. Vanderstraeten, and J. Haegeman, Gauging the variational optimization of projected entangled-pair states, arXiv:2508.10822 (2025). [arXiv:2508.10822](https://arxiv.org/abs/2508.10822)

[3] X.-Y. Zhang, Q. Yang, P. Corboz, J. Haegeman, and W. Tang, Accelerating two-dimensional tensor network optimization by preconditioning, *Physical Review B* **113**, 125111 (2026). [doi:10.1103/h396-yc28](https://doi.org/10.1103/h396-yc28)
