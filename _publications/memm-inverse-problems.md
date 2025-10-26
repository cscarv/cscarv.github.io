---
title: "The Maximum Entropy on the Mean Method for Image Deblurring"
authors: "Gabriel Rioux, Rustum Choksi, Tim Hoheisel, Pierre Maréchal, Christopher Scarvelis"
collection: publications
permalink: /publication/memm-inverse-problems
date: 2020-12-14
venue: 'Inverse Problems'
paperurl: 'https://arxiv.org/abs/2002.10434'
---
Image deblurring is a notoriously challenging ill-posed inverse problem. In recent years, a wide variety of approaches have been proposed based upon regularization at the level of the image or on techniques from machine learning. In this article, we adapt the principal of maximum entropy on the mean (MEM) to both deconvolution of general images and point spread function estimation (blind deblurring). This approach shifts the paradigm toward regularization at the level of the probability distribution on the space of images whose expectation is our estimate of the ground truth. We present a self-contained analysis of this method, reducing the problem to solving a differentiable, strongly convex finite-dimensional optimization problem for which there exists an abundance of black-box solvers. The strength of the MEM method lies in its simplicity, its ability to handle large blurs, and its potential for generalization and modifications. When images are embedded with symbology (a known pattern), we show how our method can be applied to approximate the unknown blur kernel with remarkable effects.

### Authors

Gabriel Rioux, Rustum Choksi, Tim Hoheisel, Pierre Maréchal, Christopher Scarvelis

### Technical summary

As in our earlier paper ["Blind Deblurring of Barcodes via Kullback-Leibler Divergence"](https://cscarv.github.io/publication/kl-deblurring), we use Fenchel-Rockafellar duality to transform an infinite-dimensional optimization problem over a space of probability measures into a smooth, convex, and finite-dimensional dual problem. We provide a novel stability analysis for our method and examine the role of the prior measure in our problem.
