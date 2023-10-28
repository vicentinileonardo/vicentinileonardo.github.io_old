---
layout: single
permalink: /projects/video_outpainting_localizer
title: "Video outpainting localizer"
author_profile: true
header:
  overlay_image: /assets/images/back.png
  overlay_filter: 0.5
toc: true
toc_sticky: true
toc_label: "Contents"
---


## Project description

Deep learning model for video outpainting localization. The model is able to localize the outpainted region in a video frame and to generate a binary mask that highlights the outpainted region. The implementation is based on the [RAFT model](https://arxiv.org/pdf/2003.12039.pdf). 

The main goal of the project was to modify the RAFT model and in particular we focused on data augmentation and loss function. The model has achieved a F1 score of 0.786 on the test set.

Code not available due to non-disclosure agreement.

## Report

{% raw %}
<center>  
  <a href="/project_reports/video_outpainting_localizer.pdf" target="_blank" class="btn"><i class="fa fa-file-pdf-o" style="font-size: 42px;"></i></a>
</center>
{% endraw %}


## Team and role

Team size: 2

+ The project was carried with a pair programming approach. <br>
+ I was responsible for the implementation of the data augmentation and the loss function. <br>

## Tech stack
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) 

