---
title:  "Video summarization project"
mathjax: true
layout: post
categories: media
---

<img src="https://github.com/GijungLee/Video_summarization_project/raw/main/data/Picture2.png" width="1000" height="350">


## Summary

In a video, there are so many frames that are not important to see or check contents. These unimportant frames make us waste the time. We can solve this problem by detecting important objects in a video and making video time shorter automatically. Detecting objects is performed well in computer vision. However, this good performance is for not only important objects but also unimportant objects in the video. Detecting only important objects is a challenging problem in computer vision. If we can detect only important objects in a video, there will be many applications we can apply in various fields. For example, in underwater circumstances, we can check what is happening by recording a video. However, it is difficult to sort out which parts are important and unimportant in a video. Moreover, it is waste of time to check every frame in a long video to sort the important parts. To detect important parts in a frame, the autoencoder is used for this project. Using this model, we can extract the important parts in a frame and make a video time shorter which includes only import events in a video. We can apply this project in various fields. With an unsupervised approach, we have the advantage that there is no requirement for human annotations to learn the important event in a video. With this method, the evaluation shows that the process for video summarization has two summarized videos that are an important event and an unimportant event.

- You can check the detail of the project or download the paper [here]({{ site.url }}/assets/video_report.pdf).
- You can check the code [here](https://github.com/GijungLee/Video_summarization_project).

## Results

<img src="https://github.com/GijungLee/Video_summarization_project/raw/main/data/download.png" width="1000" height="350">

### Table
| Methods | Accuracy |
| -------- | -------- |
| PL | 65.33% |
| PL + RL | 87.44% |
**Results of video summarization - PL: Pseudo labels, RL: Reconstruction loss**

<img src="https://github.com/GijungLee/Video_summarization_project/raw/main/data/Picture4.png" width="300" height="250">

## Presentations
- Presentation
{% include embed.html url="https://www.youtube.com/embed/aUFpuha3NOE" %}

- Code review
{% include embed.html url="https://www.youtube.com/embed/EzLbx3iCQic" %}
