---
title: "Graph-based mutually exciting point processes for modelling event times in docked bike-sharing systems"
collection: publications
permalink: /publication/adaoais
excerpt: 'This paper is an extension of my 2nd year group project, which consisted on fitting Hawkes processes to the London Santander Cycle bike-sharing system. In this paper we employ a spatial component in the model to take in account distances between docking stations when predicting bike usage.'
date: 1-11-2023
venue: 'Preprint (submitted for publication)'
paperurl: 'https://arxiv.org/abs/2311.00595'
citation: 'F. Sanna Passino, Y. Che, C. C. Perello, C. A. (2023). Graph-based mutually exciting point processes for modelling event times in docked bike-sharing systems.'
---

This paper introduces graph-based mutually exciting processes (GB-MEP) to model event times in network point processes, focusing on an application to docked bike-sharing systems. GB-MEP incorporates known relationships between nodes in a graph within the intensity function of a node-based multivariate Hawkes process. This approach reduces the number of parameters to a quantity proportional to the number of nodes in the network, resulting in significant advantages for computational scalability when compared to traditional methods. The model is applied on event data observed on the Santander Cycles network in central London, demonstrating that exploiting network-wide information related to geographical location of the stations is beneficial to improve the performance of node-based models for applications in bike-sharing systems. The proposed GB-MEP framework is more generally applicable to any network point process where a distance function between nodes is available, demonstrating wider applicability.

[Download paper here](https://arxiv.org/abs/2311.00595)