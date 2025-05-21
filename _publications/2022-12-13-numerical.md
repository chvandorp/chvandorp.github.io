---
title: 'Numerical methods and hypoexponential approximations for gamma distributed delay differential equations'
collection: publications
category: manuscripts
permalink: /publication/2022-12-13-numerical
excerpt: 'Integration schemes for delay-differential equations, and a relaxation of the linear chain trick that is useful for estimating the shape parameter of the Gamma distribution.'
date: 2022-12-13
venue: 'IMA Journal of Applied Mathematics'
paperurl: 'https://doi.org/10.1093/imamat/hxac027'
citation: 'Cassidy T. et al (2022). &quot;Numerical methods and hypoexponential approximations for gamma distributed delay differential equations.&quot; <i>IMA Journal of Applied Mathematics</i>. 87(6): 1043–1089.'
---

A Gamma distributed delay differential equation can be written as

$$
\frac{dX}{dt} = F\left(X(t), \int_{0}^{\infty} X(t-s) g_a^j(s)ds\right)
$$

where \\(g_a^j\\) is the PDF of the Gamma distribution with rate parameter \\(a\\)
and shape parameter \\(j\\). When \\(j \in \mathbb{N}\\), this single ODE is equivalent
with a finite-dimensional system of ODEs, which is often referred to as the 
*linear chain trick*. This "trick" is often used in modeling to get more realistic 
residence time distributions in compartmental models. By default, the residence time
in a compartment is exponentially distributed. Adding auxiliary or "pseudo" compartments
turns this into an Erlang distribution (recall that Erlang is Gamma with integer shape). 
However, what if \\(j\\) is *not* an integer? This can be useful if we want to estimate 
\\(j\\) from observations, and don't want to deal with the complications of integer-valued 
model parameters.
In this paper, we develop numerical integration schemes to solve delay differential equation.
A complication is that the delay \\(s\\) has an unbounded domain.
We also develop some approximation schemes that resemble the linear chain trick,
but allow \\(j\\) to be real-valued.