---
title: "Adaptively Optimised Adaptive Importance Samplers"
collection: publications
permalink: /publication/adaoais
excerpt: 'This paper, which stemmed out of my BSc project, introduces a new adaptive importance sampling algorithm that used adaptive optimisation to adapt the proposal distribution.'
date: 18-07-2023
venue: 'Preprint submitted for publication'
paperurl: 'TBA'
citation: 'C. C. Perello, C. A., Akyildiz, Ö. D. (2021). Adaptively Optimised Adaptive Importance Samplers.'
---

We introduce a new class of adaptive importance samplers leveraging adaptive optimisation tools, which we term AdaOAIS. We build on Optimised Adaptive Importance Samplers (OAIS), a class of techniques that adapt proposals to improve the mean-squared error of the importance sampling estimators by parameterising the proposal and optimising the χ2-divergence between the target and the proposal. We show that a naive implementation of OAIS using stochastic gradient descent may lead to unstable estimators despite its convergence guarantees. To remedy this shortcoming, we instead propose to use adaptive optimisers (such as AdaGrad and Adam) to improve the stability of the OAIS. We provide convergence results for AdaOAIS in a similar manner to OAIS. We also provide empirical demonstration on a variety of examples and show that AdaOAIS lead to stable importance sampling estimators in practice.

Here are some [slides](../files/M3R__Carlos__presentation.pdf) I made when presenting this as my BSc project.


[Download paper here](tba)

Fun fact: One of the figures generated (but now shown) in the paper is this website's [favicon](../images/website_logo.png)!