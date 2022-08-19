---
title:  "Small object detection project"
mathjax: true
layout: post
categories: media
---

![detection](https://github.com/GijungLee/Small_object_detection_project/blob/main/data/Picture1.png?raw=true)


You can check the detail of the project or download paper [here]({{ site.url }}/assets/small_Project.pdf).
You can check code [here](https://github.com/GijungLee/Small_object_detection_project).


## Summary

The detection of the small object has been challenging because of the limitation of the property of the convolutional neural network. For this project, I tried two methods to improve the performance of small objects detection. The first method is upscaling or improving the details of the image by using the concept of super-resolution. The second method is the process of performing prediction over small slices of the original image and then merging predictions from all sliced images on the original image. To detect small objects, I used the DOTA dataset which contains aerial images. For the super-resolution method, I used the Efficient Sub-pixel Convolutional Neural Network (ESPCN). With these methods, I could get 27.5% mAP, 46.4% mAP_50, 28.0% mAP_75 from 15.7% mAP, 26.3% mAP_50, 15.6% mAP_75 without any methods.

## Results
You can check the results with below links 
- Link for prediction results: [With upscaled images](https://drive.google.com/drive/folders/1tioKKtIJDxPaBKCh6-aTkmWPvy-WY_Qt?usp=sharing), [Without upscaled images](https://drive.google.com/drive/folders/1yH1gUZkCi6xn0GtAt0WTpd0Oj-PoQ3fJ?usp=sharing)

## Presentations
- Presentation
{% include embed.html url="https://www.youtube.com/embed/aOLFkBbP3GQ" %}
{% include embed.html url="https://www.youtu.be/embed/aOLFkBbP3GQ" %}
{% include embed.html url="https://youtu.be/embed/aOLFkBbP3GQ" %}

- Code review
{% include embed.html url="https://www.youtube.com/embed/8p8K7BRCqmI" %}


## Reference
1. [How to detect small objects in (very) large images](https://blog.ml6.eu/how-to-detect-small-objects-in-very-large-images-70234bab0f98)
2. [SAHI: Slicing Aided Hyper Inference](https://github.com/obss/sahi/blob/main/demo/slicing.ipynb)
