---
title: "A Continuous Time Framework for Discrete Denoising Models"
collection: publications
author: Campbell. A, Benton. J, De Bortoli. V, Rainforth. T, Deligiannidis. G, Doucet. A
link: https://arxiv.org/abs/2205.14987
venue: 'NeurIPS 2022 (Oral)'
order: 2
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

We provide the first complete continuous time framework for denoising diffusion models of discrete data. This is achieved by formulating the forward noising process and corresponding reverse time generative process as Continuous Time Markov Chains (CTMCs). The model can be efficiently trained using a continuous time version of the ELBO. We simulate the high dimensional CTMC using techniques developed in chemical physics and exploit our continuous time framework to derive high performance samplers that we show can outperform discrete time methods for discrete data. The continuous time treatment also enables us to derive a novel theoretical result bounding the error between the generated sample distribution and the true data distribution. 