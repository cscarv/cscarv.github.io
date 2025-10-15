---
title: "Sensitivity Analysis for Diffusion Models"
collection: publications
permalink: /publication/sensitivity-analysis
date: 2025-09-27
venue: "Under review"
paperurl: 'https://www.arxiv.org/abs/2509.23092'
---
Training a diffusion model approximates a map from a data distribution to the optimal score function for that distribution. Can we differentiate this map? If we could, then we could predict how the score, and ultimately the model's samples, would change under small perturbations to the training set before committing to costly retraining. We give a closed-form procedure for computing this map's directional derivatives, relying only on black-box access to a pre-trained score model and its derivatives with respect to its inputs. We extend this result to estimate the sensitivity of a diffusion model's samples to additive perturbations of its target measure, with runtime comparable to sampling from a diffusion model and computing log-likelihoods along the sample path. Our method is robust to numerical and approximation error, and the resulting sensitivities correlate with changes in an image diffusion model's samples after retraining and fine-tuning.

### Authors

Christopher Scarvelis, Justin Solomon
