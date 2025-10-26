---
title: "Blind Deblurring of Barcodes via Kullback-Leibler Divergence"
authors: "Gabriel Rioux, Christopher Scarvelis, Rustum Choksi, Tim Hoheisel, Pierre Maréchal"
collection: publications
permalink: /publication/kl-deblurring
date: 2021-01-01
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8758192'
---

Barcode encoding schemes impose symbolic constraints which fix certain segments of the image. We present, implement, and assess a method for blind deblurring and denoising based entirely on Kullback-Leibler divergence. The method is designed to incorporate and exploit the full strength of barcode symbologies. Via both standard barcode reading software and smartphone apps, we demonstrate the remarkable ability of our method to blindly recover simulated images of highly blurred and noisy barcodes. As proof of concept, we present one application on a real-life out of focus camera image.

### Authors

Gabriel Rioux, Christopher Scarvelis, Rustum Choksi, Tim Hoheisel, Pierre Maréchal

### Background

QR codes enable businesses to seamlessly link their physical and digital marketing campaigns by offering audiences the option to quickly access a business' website (or any other digital asset) using their smartphone.

Camera blur is a common roadblock in this process, frustrating consumers and making them less likely to follow through with their interaction with a digital campaign. An effective deblurring algorithm mitigates this issue by allowing the QR code reader to receive a usable signal even when the underlying image of the QR code is blurry.

### Technical summary

Instead of taking the usual approach of minimizing a regularized loss over the space of barcodes, we pose the deblurring problem as an optimization problem over the space of probability measures on the space of barcodes. We regularize our problem using the Kullback-Leibler divergence with respect to a prior that encodes structural information regarding valid barcodes.

We use Fenchel-Rockafellar duality to transform this infinite-dimensional problem into a smooth, convex, and finite-dimensional optimization problem which can be solved using standard gradient-based optimizers. The resulting algorithm is easy to implement and achieves state-of-the-art results in the blind deblurring of QR codes.

This synthetic example demonstrates the output of our algorithm (right) given a QR code that has been subjected to severe motion blur (left):

![Blurry QR code](/images/Var(0.01)Width(29)Blurw(21)Upscl(3)blurred.png "Blurry QR code")
![Output of our algorithm](/images/FinalVar(0.01)Width(29)Blurw(21)Upscl(3)normalizeddeblurred.png "Ours")

[Download paper here](http://www.math.mcgill.ca/rchoksi/pub/KL.pdf)
