---
title: "Is Your Diffusion Model Actually Denoising?"
collection: publications
permalink: /publication/actually-denoising
date: 2025-09-18
venue: "NeurIPS"
paperurl: 'https://openreview.net/forum?id=Z2lWGBx2v2'
---
We study the inductive biases of diffusion models with a conditioning-variable, which have seen widespread application as both text-conditioned generative image models and observation-conditioned continuous control policies. We observe that when these models are queried conditionally, their generations consistently deviate from the idealized "denoising" process upon which diffusion models are formulated, inducing disagreement between popular sampling algorithms (e.g. DDPM, DDIM). We introduce Schedule Deviation, a rigorous measure which captures the rate of deviation from a standard denoising process, and provide a methodology to compute it. Crucially, we demonstrate that the deviation from an idealized denoising process occurs irrespective of the model capacity or amount of training data. We posit that this phenomena occurs due to the difficulty of bridging distinct denoising flows across different parts of the conditioning space and show theoretically how such a phenomena can arise through an inductive bias towards smoothness.

### Authors

Daniel Pfrommer, Zehao Dou, Christopher Scarvelis, Max Simchowitz, Ali Jadbabaie
