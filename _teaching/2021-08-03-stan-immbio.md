---
title: "SMB workshop: Stan for Immunobiology"
collection: teaching
type: "Workshop"
permalink: /teaching/2021-08-03-stan-immbio
venue: "SMB, Immunobiology and Infection"
date: 2021-08-03
location: "Online"
---


For the Immunobiology and Infection subgroup of the Society for Mathematical Biology (SMB), 
I taught a workshop for attendees interested in learning to use Stan.

Stan is a powerful platform for statistical modeling and high-performance statistical computation. It is used primarily for Bayesian statistical modeling, data analysis, parameter estimation including for ODE models, and to make predictions, in the social, biological, and physical sciences.


Why Stan?
---------

Stan is a powerful platform for Bayesian statistical modeling. Bayesian statistics has certain benefits over frequentist approaches, such as the possibility to incorporatie prior knowledge in the model, and access to the full posterior density of the parameters. However, in most use cases, Bayesian inference requires Monte Carlo methods that are computationally intensive and time consuming. One aspect that makes Stan so appealing is a very effective implementation of the highly efficient Hamiltonian Monte Carlo algorithm which to a large extent automatically tunes algorithmic parameters. 

The second appeal of Stan is that it provides a highly expressive and flexible programming language with built-in support for many statistical distributions, and auxiliary functions such as ODE integrators.

The versitility of the Stan language allows for the implementation of highly complex models that are common in immunobiology. Often, we encounter multi-dimensional time-series data with repeated experiments and multiple covariates. However, for modelers that are new to Stan, implementing such a model can be very challenging. The webinar starts with the basics, and will then gradually move to more complex models with examples from e.g. viral dynamics and epidemiology.

Jupyter notebooks with all the course material and exercises are available on [github](https://github.com/chvandorp/stan-immbio)
