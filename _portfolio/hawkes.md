---
title: "Fitting Hawkes processes to London Santander bike-sharing data"
excerpt: "Second year project at Imperial College London, supervised by [Prof Francesco Sanna Passino](https://fraspass.github.io/)."
collection: portfolio
---

In this project, we (a group of 5 students led by myself and [Mathieu Deschenes](https://www.linkedin.com/in/mathieu-deschenes/?originalSubdomain=uk) ) fitted Self-Exciting and Mutually-Exciting Hawkes processes to London Santander bike-sharing data. A short abstract of the project is given below:

In this report, we introduce the theory of Self-Exciting (SE) and Mutually Exciting (ME) point processes, which are powerful mathematical concepts with a wide range of applications across areas such a earthquake modelling and finance. We apply the theory to formulate 5 models describing Santander cycle hires from stations across London, with the model making use of both SE and ME behaviour demonstrating excellent performance. For each model, we derive a recursive form for the log-likelihood which allows for fast computation of optimal parameters via maximum likelihood estimation, using nonlinear optimisation and the Nelder-Mead algorithm. Finally, improvements to these models and other ways to measure their goodness of fit are discussed. Applications for the successful models include optimal bike allocation and re-balancing. Additionally, the theoretical results are general enough to be applicable to any system which might demonstrate SE or ME behaviour. 

The repository for the code written for this project is available [here](https://github.com/carlosaccp/Santander-SE-ME) alongside with the final report, which can be found through [this link](https://github.com/carlosaccp/Santander-SE-ME/blob/main/report.pdf).

