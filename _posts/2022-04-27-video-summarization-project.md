---
title:  "Small object detection project"
mathjax: true
layout: post
categories: media
---

![detection](https://github.com/GijungLee/Video_summarization_project/raw/main/data/Picture2.png)


## Summary

In a video, there are so many frames that are not important to see or check contents. These unimportant frames make us waste the time. We can solve this problem by detecting important objects in a video and making video time shorter automatically. Detecting objects is performed well in computer vision. However, this good performance is for not only important objects but also unimportant objects in the video. Detecting only important objects is a challenging problem in computer vision. If we can detect only important objects in a video, there will be many applications we can apply in various fields. For example, in underwater circumstances, we can check what is happening by recording a video. However, it is difficult to sort out which parts are important and unimportant in a video. Moreover, it is waste of time to check every frame in a long video to sort the important parts. To detect important parts in a frame, the autoencoder is used for this project. Using this model, we can extract the important parts in a frame and make a video time shorter which includes only import events in a video. We can apply this project in various fields. With an unsupervised approach, we have the advantage that there is no requirement for human annotations to learn the important event in a video. With this method, the evaluation shows that the process for video summarization has two summarized videos that are an important event and an unimportant event.

- You can check the detail of the project or download the paper [here]({{ site.url }}/assets/small_Project.pdf).
- You can check the code [here](https://github.com/GijungLee/Small_object_detection_project).

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
