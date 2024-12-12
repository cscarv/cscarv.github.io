---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
published: true
redirect_from:
  - /research
---


Machine learning has recently made great progress by following a ["straightforward recipe"](https://arxiv.org/abs/1712.00409):

- Search for improved model architectures,
- Create large training datasets, and
- Scale computation.

This recipe has been wildly successful: It’s delivered software that can generate realistic images, chatbots that can solve challenging math problems [roughly on par with a (mediocre) grad student](https://mathstodon.xyz/@tao/113132502735585408), and algorithms that can generate high-quality 3D assets based on a single 2D image.

**But this recipe doesn’t always work!** In my research, I’ve identified several real-world machine learning problems where naively scaling up training data, model size, or the number of training iterations is either impossible, fails to yield the promised improvements, or even leads to unexpected – and unwanted – results.

For example:

- Training a [3D orienter](https://arxiv.org/abs/2410.02101) on symmetric shapes yields incorrect solutions – no matter how much training data and compute you throw at the problem.
- Training a neural network with a [natural low-rank regularizer](https://arxiv.org/abs/2405.14544) is intractable given any currently feasible compute budgets.
- [Training a diffusion model to optimality](https://arxiv.org/abs/2310.12395) – with enough training iterations and a sufficiently large, high-capacity neural network, makes it unable to generate new samples.

For each of these problems, I’ve developed alternative approaches that avoid these fundamental issues and that are then amenable to scale.

My work complements scale. I aim to build a fundamental understanding of machine learning problems to answer questions like...

- *Are* we solving the problem we think we’re solving?
- *Can* we solve that problem?
- Should we be solving a *different* problem?

...before spending valuable time and compute training – and inevitably debugging – a neural pipeline.
