---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
published: true
redirect_from:
  - /research
---

Some of the most exciting recent developments in machine learning exploit the *geometry* of objects like molecules, shapes, and social networks to:

- [Discover new antibiotics](https://www.sciencedirect.com/science/article/pii/S0092867420301021)
- [Predict the physics of glass](https://www.nature.com/articles/s41567-020-0842-8)
- [Generate product recommendations at massive scale](https://www.amazon.science/publications/p-companion-a-principled-framework-for-diversified-complementary-product-recommendation)
- [Predict protein interaction sites](https://openaccess.thecvf.com/content/CVPR2021/papers/Sverrisson_Fast_End-to-End_Learning_on_Protein_Surfaces_CVPR_2021_paper.pdf)
- [Classify particle jets in the Large Hadron Collider](https://arxiv.org/abs/1902.08570)
- [Predict functional regions in the cerebral cortex](https://research.facebook.com/publications/convolutional-neural-networks-for-mesh-based-parcellation-of-the-cerebral-cortex/)
- [Predict molecular dynamics](https://www.nature.com/articles/s41467-022-29939-5)

But oftentimes, **the default geometry of our data isn’t right for the problem we’d like to solve.** 

### Some examples

- Many real-world graphs have the *small-world property*. Most nodes are close to one another in these graphs, causing graph neural nets to exhibit pathological behavior like *over-smoothing* and *over-squashing*. These phenomena make it difficult to transmit information between distant node pairs.
- Assuming a Euclidean geometry for *mass spectra* hinders the performance of machine learning methods for biochemical problems like mass spectral library search and molecular property prediction.
- More broadly, we might believe that our data lies on a thin manifold in high-dimensional space but have no way to describe it. Learning a *generative model* of our data distribution gives a path towards a description of our data's geometry.

Informed by these issues, my research centers on developing methods for **learning geometric structure for non-Euclidean data** that's well-adapted to the tasks we'd like to solve.

### My active projects

- Graph reweighting to align a graph's geometry with inter-node affinities. These affinities typically come from an attention mechanism that compares features between all pairs of nodes in the graph.
- Using contrastive learning to learn a chemically-informative geometry for mass spectra.
- Flow-based generative modeling using optimal transport. We hope to use our methods to efficiently model distributions over non-Euclidean objects like point clouds.
