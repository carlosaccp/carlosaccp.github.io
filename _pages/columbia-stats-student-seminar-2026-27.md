---
layout: archive
title: "Columbia Stats Student Seminar 2026-27"
permalink: /columbia-stats-student-seminar-2026-27/
author_profile: true
---

{% include base_path %}

<style>
.abstract-toggle {
  cursor: pointer;
  transition: color 0.15s ease;
}

.abstract-toggle:hover {
  color: #75AADB;
  text-decoration-thickness: 2px;
}

.title-label {
  font-weight: normal;
  color: #777;
}
</style>

I will be organising the Columbia Stats Student Seminar in 2026/27, alongside [David Metrick](https://stat.columbia.edu/people/name/david-metrick/). The seminar takes place every Wednesday from 12PM-1PM in the Statistics department. If you're interested in attending or giving a talk, please feel free to reach out via email.

# Seminar Schedule

## September 16, 2026: [Cindy Rush](https://www.columbia.edu/~cgr2130/)
### Title: <span style="font-weight: normal;">Spectral Geometry and the Limits of Convex Regularization in High-Dimensional Regression</span>

<details>
<summary class="abstract-toggle"><u>Abstract</u></summary>

In this talk I will demonstrate how the spectrum of a high-dimensional design controls the best asymptotic risk achievable by convex regularization. For iid Gaussian designs, Celentano and Montanari (2022) established a related convex lower bound, but the spectral shape is then fixed by the sample-to-dimension ratio. We instead study right-rotationally invariant designs with an otherwise arbitrary limiting squared-singular-value distribution. Our main result shows that every estimator in a broad class of separable convex penalized least-squares procedures has asymptotic mean-squared error at least that of a corresponding Bayes message-passing estimator. The resulting lower bound depends on the full spectrum, not only on the sample-to-dimension ratio or average measurement strength. In particular, at fixed average measurement strength, a mean-preserving spread of the squared singular values worsens the best possible convex risk: weakly measured directions are more damaging than strongly measured directions are beneficial. I will explain the main ideas behind this spectral comparison and how vector approximate message passing separates the effects of the signal prior from those of the design spectrum. This is joint work with <a href="https://stat.columbia.edu/department-directory/current-phd-students/name/audrey-yang/">Audrey Yang</a> and <a href="https://stat.columbia.edu/department-directory/current-doctoral-students/name/baichen-tan/">Baichen Tan</a>.

</details>

**Food:** Massawa

---

## September 23, 2026: [Jeremy Shen](https://jeremyshen.com/)
### Title: <span style="font-weight: normal;">Three Statistical Problems in Finance</span>

<details>
<summary class="abstract-toggle"><u>Abstract
</u></summary>
We introduce three high-level statistical problems in quantitative finance. These problems will be motivated by tracing our roots back to modern portfolio theory along with its main economic and statistical critiques. For each of the problems, we will sketch approaches to its modeling, and highlight particularities that make the modeling process different from other more commonly-discussed applications of statistics. The contents of this talk will be based on public domain work.
</details>

**Food:** Han Dynasty

---

## September 30, 2026: [Steven Campbell](https://www.stevenacampbell.com/)
### Title: <span style="font-weight: normal;">Statistical Embeddings and Sequential Inference for Win-Martingales</span>

<details>
<summary class="abstract-toggle"><u>Abstract</u></summary>
<p>An evolving probability for a binary event is naturally modeled as a bounded (so-called “win-”) martingale. Motivated by prediction markets and recent work on Aldous’ "<a href="https://arxiv.org/abs/2305.14037">most exciting game</a>," we consider two questions. Can a given win-martingale be realized as the exact Bayesian posterior of a sequential experiment? And, if observing the process is costly, when should a decision maker stop and make a prediction?</p>

<p>We answer both questions for a broad class of martingale diffusions with separable volatility. We construct an explicit binary diffusion experiment whose posterior has the prescribed dynamics and show that the optimal strategy for a large class of sequential decision problems is to stop and predict according to two time-dependent thresholds. For this class of problems, we establish regularity and a unique integral equation characterization of the resulting stopping boundaries, and illustrate how the rate of information arrival can produce shrinking, expanding, or nonmonotone continuation regions. This is joint work with Karl Kristian Engelund (University of Copenhagen.)</p>

</details>

**Food:** Dig Inn

---

## October 7, 2026: [Shunan Sheng](https://scholar.google.com/citations?user=GdfBESAAAAAJ&hl=en)
### Title: <span style="font-weight: normal;">Stability, instability, and extensions of variational inference</span>

<details>
<summary class="abstract-toggle"><u>Abstract</u></summary>
<p>Variational inference (VI) is a popular alternative to Markov chain Monte Carlo (MCMC) for approximating high-dimensional target distributions. At its core, VI approximates a high-dimensional target distribution—typically specified via an unnormalized density—by a simpler variational family. Despite its empirical success, the theoretical properties of variational inference have only recently begun to be understood.
In the first part of the talk, I will discuss the robustness of mean-field variational inference (MFVI) through the lens of optimal transport. We aim to answer the following question: How sensitive are variational solutions to small perturbations of the target measure arising from changes in the underlying statistical model, likelihood, or prior? The main message is that stability depends sharply on the geometry of the target distribution. When the target is strongly log-concave, MFVI is quantitatively stable under perturbations of the target measure, yielding robustness guarantees for approximate Bayesian inference. In contrast, even simple non-log-concave targets, such as mixtures of two Gaussians, can cause MFVI to exhibit an instability known as mode collapse, revealing a fundamental lack of robustness to multimodality.</p>
<p>In the second part of the talk, I will present our work on the statistical and computational theory of a class of structured variational inference methods in which the variational family consists of all star-shaped distributions. We establish quantitative approximation guarantees and provide a polynomial-time algorithm for solving the VI problem when the target distribution is strongly log-concave. We also discuss concrete examples, including generalized linear models with Gaussian likelihoods.
This talk is based on joint work with Bohan Wu, Alberto González-Sanz, Marcel Nutz, Sinho Chewi, Binghe Zhu, and Aram Pooladian.</p>
</details>

---

## October 14, 2026: [Ivan Corwin](https://www.math.columbia.edu/~corwin/), [Chris Harshaw](https://www.chrisharshaw.com/), [Marcel Nutz](https://www.marcelnutz.com/), [Tian Zheng](https://sites.stat.columbia.edu/tzheng/author/tian-zheng/)
### Title: <span style="font-weight: normal;">Panel on Stat PhD and AI</span>

<details>
<summary class="abstract-toggle"><u>Abstract</u></summary>
An interactive discussion on what our Stat PhD should look like in the presence of AI.
</details>

---

## October 21, 2026: [Chris Harshaw](https://www.chrisharshaw.com/)
### Title: <span style="font-weight: normal;">Minimax Rates for Estimating Causal Effects in Network Experiments</span>

<details>
<summary class="abstract-toggle"><u>Abstract</u></summary>
Network experiments are used throughout the social and medical sciences to investigate causal effects under the presence of interference. While a large body of work has developed improved statistical procedures, the fundamental limits of statistical estimation in these settings is less well understood. In this talk, I will introduce a design-based theory of minimax risk for network experiments under an arbitrary neighborhood interference model. Our notion of minimax risk describes the optimal precision among all statistical procedures for investigating a particular causal effect on the observed interference network. We show that the minimax risk is a function of the corresponding conflict graph, which captures inherent unobservability of estimand-relevant potential outcomes given the observed interference network. Our main contribution is a series of upper and lower bounds on the minimax rate in terms of local and global connectivity properties of the conflict graph. To illustrate their utility, we apply these general results to obtain minimax analyses for two commonly studied effects: the direct treatment effect and global average treatment effect.
</details>

---

## October 28, 2026: [Alan Gelfand](https://stat.duke.edu/research/gelfand) (Duke)
### Title: <span style="font-weight: normal;">Spatial and Spatio-temporal Modeling for Beta Diversity</span>

<details>
<summary class="abstract-toggle"><u>Abstract</u></summary>
<p>Turnover, or change in the composition of species over space and time, is one of the primary ways to define beta diversity. Inferring what factors impact beta diversity is important not only for understanding biodiversity processes but also for conservation planning. A popular approach to understanding the drivers of compositional turnover is generalized dissimilarity modeling (GDM). However, the current GDM approach has several limitations. We provide an alternative approach that remedies these issues. In particular, we propose a model with a flexible mean function, complex spatial and spatio-temporal random effects that capture dependence unaccounted for by explanatory variables, and heterogeneous variance structure. Further, these features are offered in a model that can handle a large incidence of total dissimilarity through “1-inflation.” Such inflation would be expected in highly biodiverse areas with steep turnover gradients in space and time.</p>

<p>The models are implemented in a Bayesian framework, employing hierarchical specifications to yield full regression and spatial predictive inference, both with associated uncertainties. We illustrate the approach by examining dissimilarity in plant abundance surveys from the Greater Cape Floristic Region (GCFR) of South Africa. We model both at the species scale and the family scale, selecting the best model using out-of-sample predictive performance. Notably, the spatial random effects play a more important role in the modeling than all of the environmental variables. (This is joint work with Phil White, Henry Frye, Jasper Slingsby, and John Silander.)</p>
</details>

---

## November 4, 2026: [Genevera Allen](https://genevera-allen.com/)
### Title: <span style="font-weight: normal;">TBA</span>

---

## November 11, 2026: TBA
### Title: <span style="font-weight: normal;">TBA</span>

---

## November 18, 2026: TBA
### Title: <span style="font-weight: normal;">TBA</span>

---

## December 2, 2026: TBA
### Title: <span style="font-weight: normal;">TBA</span>

---

## December 9, 2026: TBA
### Title: <span style="font-weight: normal;">TBA</span>