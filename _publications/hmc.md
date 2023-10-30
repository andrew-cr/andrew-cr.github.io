---
title: "A Gradient Based Strategy for Hamiltonian Monte Carlo Hyperparameter Optimization"
collection: publications
author: Campbell. A*, Chen. W*, Stimper. V*, Hernández-Lobato. JM, Zhang. Y
link: http://proceedings.mlr.press/v139/campbell21a/campbell21a.pdf
# permalink: /publication/hmc
# excerpt: 'A Gradient Based Strategy for Hamiltonian Monte Carlo Hyperparameter Optimization'
venue: 'ICML 2021'
order: 4
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Hamiltonian Monte Carlo (HMC) is one of the most successful sampling methods in machine learning. However, its performance is significantly affected by the choice of hyperparameter values. Existing approaches for optimizing the HMC hyperparameters either optimize a proxy for mixing speed or consider the HMC chain as an implicit variational distribution and optimize a tractable lower bound that can be very loose in practice. Instead, we propose to optimize an objective that quantifies directly the speed of convergence to the target distribution. Our objective can be easily optimized using stochastic gradient descent. We evaluate our proposed method and compare to baselines on a variety of problems including sampling from synthetic 2D distributions, reconstructing sparse signals, learning deep latent variable models and sampling molecular configurations from the Boltzmann distribution of a 22 atom molecule. We find that our method is competitive with or improves upon alternative baselines in all these experiments.
