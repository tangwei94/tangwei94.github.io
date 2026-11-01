---
layout: page
title: Tensor networks for disordered systems
description: Disorder-averaged quantum many-body physics directly in the thermodynamic limit.
importance: 3
category: research
published: true
---

Disorder plays a central role in quantum many-body physics, giving rise to phenomena such as localization, glassy dynamics, and infinite-randomness criticality. Despite its importance, numerical simulations of disordered quantum systems remain challenging. Conventional approaches typically rely on explicit sampling over many disorder realizations in finite-size systems, which is computationally expensive and becomes less reliable near disorder-dominated critical points due to rare-region effects and broad probability distributions.

Recently, we developed a tensor network method that computes disorder-averaged expectation values in random spin chains without explicit disorder sampling [1]. By exploiting **statistical translational invariance**, the algorithm operates directly in the thermodynamic limit using translationally invariant tensor networks. We demonstrated the effectiveness of this approach on random spin chains, including the infinite-randomness critical point of the random transverse-field Ising model, opening a new tensor network route to disordered quantum matter.

### References {#references-disorder}

- **[1]** K. Vervoort, W. Tang, and N. Bultinck, _Extracting average properties of disordered spin chains with translationally invariant tensor networks_, [arXiv:2504.21089 (2025)](https://arxiv.org/abs/2504.21089).
