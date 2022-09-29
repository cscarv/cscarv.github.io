---
title: "Riemannian Metric Learning via Optimal Transport"
collection: publications
permalink: /publication/memm-inverse-problems
date: 2022-05-18
venue: 'ICLR 2023 (submitted)'
paperurl: [https://arxiv.org/abs/2205.09244]
---

We introduce an optimal transport-based model for learning a metric tensor from cross-sectional samples of evolving probability measures on a common Riemannian manifold. We neurally parametrize the metric as a spatially-varying matrix field and efficiently optimize our model's objective using a simple alternating scheme. Using this learned metric, we can nonlinearly interpolate between probability measures and compute geodesics on the manifold. We show that metrics learned using our method improve the quality of trajectory inference on scRNA and bird migration data at the cost of little additional cross-sectional data.

### Authors

Christopher Scarvelis, Justin Solomon

### Technical summary

Optimal transport distances depend critically on the geometry of the ground space. Given pairs of probability measures that we believe are close, we can solve an inverse problem: Determine a suitable geometry for the ground space such that the pairs of measures have small average optimal transport distance. We solve a version of this problem where the ground space's geometry is parametrized by a Riemannian metric.

[Download paper here](https://arxiv.org/abs/2205.09244)
