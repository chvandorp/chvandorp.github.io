---
title: 'Bayesian Multi-dimensional scaling (MDS)'
date: 2018-06-03
permalink: /posts/2018/06/bayesian-mds/
tags:
  - Stan
  - multi-dimensional scaling
  - antigenic cartography
---

Antigenic cartography maps viruses and sera to a two-dimensional space to 
visualize their relation and the pace of antigenic drift.
As antigens and antibodies are typically very high dimensional objects,
special methods to embed them into lower dimensional spaces are required.
MDS is one such method. In this post, I show how to implement a Bayesian version
of MDS and apply this to influenza data.

The post is hosted on my [tbz533 blog](https://tbz533.blogspot.com/2018/06/easy-bayesian-multidimensional-scaling.html)