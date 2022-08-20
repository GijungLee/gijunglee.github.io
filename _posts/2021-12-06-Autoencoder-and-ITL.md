---
title:  "Kmnist AutoEncoder and ITL project"
mathjax: true
layout: post
categories: media
---

<img src="https://github.com/GijungLee/Kmnist_AutoEncoder_Project/raw/main/data/Picture1.png" width="1000" height="350">


## Summary

We investigate the use of Autoencoders for reducing the dimensionality of KMNIST digits data set to improve classification performance. We compare the classification performance to the use of Convolutional Neural Networks (CNNs). We further introduce an information theory regularizer on the autoencoder. We force the autoencoder to learn latents on a 3d swiss roll prior and decode the images. Lastly, we introduce a Gaussian and a Gaussian Mixture Model Prior to investigate its effect on unsupervised clustering of the latent space. This work is presented as the final project for EEL6814 – Deep Learning Course.

- You can check the detail of the project or download the paper [here]({{ site.url }}/assets/Project_2_KMNIST_MAYAR_GIJUNG_final.pdf).
- You can check the code [here](https://github.com/GijungLee/Kmnist_AutoEncoder_Project).

## Results
We enforce the model to maximize the entropy of the latent code distribution which helps in spreading out the latent while at the same time minimizing the cross-entropy between the latent code and the prior distributions which makes latent codes fit the prior distribution better.

- Swiss Roll

<img src="https://github.com/GijungLee/Kmnist_AutoEncoder_Project/raw/main/data/Picture1.png" width="1000" height="350">

- Gaussian

<img src="https://github.com/GijungLee/Kmnist_AutoEncoder_Project/raw/main/data/Picture2.png" width="1000" height="350">

<img src="https://github.com/GijungLee/Kmnist_AutoEncoder_Project/raw/main/data/Picture3.png" width="350" height="350">

Samples from a linear walk over the swiss-roll. Right to left is going along the linear direction of the manifold. Top to bottom is going along the rotating direction of the manifold.