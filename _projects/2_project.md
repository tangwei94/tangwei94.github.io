---
layout: page
title: Continuous tensor networks
description: Continuous matrix product states and operators for continuum quantum systems and finite temperatures.
importance: 2
category: research
published: true
---

In continuum quantum systems such as ultracold atomic gases and $(1+1)$-dimensional quantum field theories, the spatial degrees of freedom are intrinsically continuous. **Continuous matrix product states (cMPS)** provide a variational wave function ansatz that operates directly in the continuum limit without spatial discretization. To improve the efficiency of cMPS calculations, we employed Riemannian optimization and preconditioning techniques, enabling accurate studies of emergent Kac-Moody symmetries in one-dimensional bosonic systems [1]. We further extended this framework to multi-component cMPS, providing an effective numerical tool for quantum mixtures such as multi-species bosonic gases [2].

Continuous tensor networks also arise naturally in quantum lattice models at finite temperatures, where the path-integral representation of the partition function is continuous along the imaginary-time direction. We proposed the **continuous matrix product operator (cMPO)** approach to finite-temperature quantum states by taking the continuous-time limit of the partition-function tensor network, where the dominant eigenvector of the cMPO transfer matrix is obtained by variationally optimizing a uniform cMPS [3]. This method provides direct access to the thermodynamics of one- and quasi-one-dimensional quantum systems and has been applied to field-theoretic problems such as the $(1+1)$-dimensional $O(3)$ nonlinear $\sigma$-model with a $\theta=\pi$ topological term [4].

### References {#references-continuous}

- **[1]** W. Tang and J. Haegeman, _Kac-Moody symmetries in one-dimensional bosonic systems_, [Physical Review B **108**, 035153 (2023)](https://doi.org/10.1103/PhysRevB.108.035153).
- **[2]** W. Tang, B. Tuybens, and J. Haegeman, _Numerical study of boson mixtures with multi-component continuous matrix product states_, [arXiv:2512.24998 (2025)](https://arxiv.org/abs/2512.24998).
- **[3]** W. Tang, H.-H. Tu, and L. Wang, _Continuous matrix product operator approach to finite temperature quantum states_, [Physical Review Letters **125**, 170604 (2020)](https://doi.org/10.1103/PhysRevLett.125.170604).
- **[4]** W. Tang, X. C. Xie, L. Wang, and H.-H. Tu, _Tensor network simulation of the $(1+1)$-dimensional $O(3)$ nonlinear $\sigma$-model with $\theta=\pi$ term_, [Physical Review D **104**, 114513 (2021)](https://doi.org/10.1103/PhysRevD.104.114513).
