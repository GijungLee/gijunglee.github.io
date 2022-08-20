---
title:  "Kmnist AutoEncoder and ITL project"
mathjax: true
layout: post
categories: media
---

<img src="https://github.com/GijungLee/Kmnist_AutoEncoder_Project/raw/main/data/Picture1.png" width="1000" height="350">


## Summary

We investigate the use of Autoencoders for reducing the dimensionality of KMNIST digits data set to improve classification performance. We compare the classification performance to the use of Convolutional Neural Networks (CNNs). We further introduce an information theory regularizer on the autoencoder. We force the autoencoder to learn latents on a 3d swiss roll prior and decode the images. Lastly, we introduce a Gaussian and a Gaussian Mixture Model Prior to investigate its effect on unsupervised clustering of the latent space. This work is presented as the final project for EEL6814 – Deep Learning Course.

- You can check the detail of the project or download the paper [here]({{ site.url }}/assets/video_report.pdf).
- You can check the code [here](https://github.com/GijungLee/Video_summarization_project).

## Results

<img src="https://github.com/GijungLee/Video_summarization_project/raw/main/data/download.png" width="1000" height="350">

| Methods | Accuracy |
| -------- | -------- |
| PL | 65.33% |
| PL + RL | 87.44% |

Results of video summarization. PL: Pseudo labels, RL: Reconstruction loss

<img src="https://github.com/GijungLee/Video_summarization_project/raw/main/data/Picture4.png" width="300" height="250">
