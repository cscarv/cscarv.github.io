---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
published: true
redirect_from:
  - /research
---


Generative models now power systems that write code, generate photorealistic images, and design new molecules and mechanical parts. However, this success rests on a striking paradox: Generative models are built by training neural networks to optimize simple objectives on finite datasets, but these objectives are optimized in theory by trivial models that memorize their training data and cannot generate new content. **Generative models succeed in practice *because they fail* to reach these trivial optima**, and the causes of this benign failure are poorly understood.

My research seeks to resolve this paradox by developing **a predictive theory of generative models’ behavior** that natively accounts for the role of neural architectures, the training procedure, and the training data. In one prong of my research agenda, I study how these factors interact to produce models that *generalize* by generating new content instead of regurgitating training data. In a complementary prong, I zoom in on the impact of the training data on a particular trained model's behavior. Here, I study how the composition of the training set influences the samples created by a generative model.

Some of my recent work includes:

- A theoretical characterization of a diffusion model's samples under a *smoothness* bias, which is shared by common neural architectures. ([Closed-Form Diffusion Models](https://arxiv.org/abs/2310.12395), TMLR 2025)
- A natural regularizer that exploits the compositional structure of neural networks to efficiently control their local geometry. ([Nuclear Norm Regularization for Deep Learning](https://arxiv.org/abs/2405.14544), NeurIPS 2024)
- An exact sensitivity analysis for diffusion models, which can be used to predict how a diffusion model's samples respond to changes in its training data. ([Sensitivity Analysis for Diffusion Models](https://arxiv.org/abs/2509.23092), under review)

I've also worked in [optimal transport](https://arxiv.org/abs/2205.09244) and in [3D deep learning](https://arxiv.org/abs/2410.02101).
