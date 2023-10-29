---
layout: single
permalink: /projects/galaxies_image_classification
title: "Galaxies Image Classification"
author_profile: true
header:
  overlay_image: /assets/images/back.png
  overlay_filter: 0.5
toc: true
toc_sticky: true
toc_label: "Contents"
---

<!-- ### [ Jun. 2021 - Jul. 2021 ] -->

## Project description

The goal of this project is to classify galaxies images into **10 different classes**. In order to achieve this goal, several models have been trained and tested, as explained in the report. The final model is leveraging a pre-trained **VGG19** network as a feature extractor and **Support Vector Machines** as a classifier. The model has been trained on a dataset of 9928 images, validated on 2487 images and tested on 5321 images. The model has achieved a sample-wise accuracy of 85.6% and a class-wise accuracy of 83.8% on the test set.

## Repository and Report

{% raw %}
<center>
  <a href="https://github.com/vicentinileonardo/galaxies-image-classification" target="_blank" class="btn"><i class="fa fa-github" style="font-size: 42px;"></i></a>
  <a href="/projects/reports/galaxies_image_classification.pdf" target="_blank" class="btn"><i class="fa fa-file-pdf-o" style="font-size: 42px;"></i></a>
</center>
{% endraw %}

## Team and role

Team size: 1 person

+ I was responsible for the whole project, from model exploration to final implementation. <br>

## Tech stack

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) 
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) 
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white)
