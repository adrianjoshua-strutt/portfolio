---
layout: post
title: "Wound Detection for Mobile Devices"
thumbnail: "../assets/images/detection.jpg"
categories:
  - university
tags:
  - university
---

## TL;DR

- Evaluate wound detection on mobile devices combined with wound segmentation
- SSDlite, YOLOv3 with a MobileNetV2 backbone, and YOLOv5
- FUSeg dataset adapted to the task of wound localization (+ Data Sanity Check)
- Hyperparameter studies, 5-fold cross-validation, and segmentation feasibility experiment
- Using PyTorch, Pandas, Numpy, and OpenCV

## Abstract

Chronic wounds pose significant challenges to healthcare systems and individual well-being, with substantial economic burdens. Manual segmentation of such wounds is labor-intensive and costly. This study aims to automate wound localization on mobile devices to simplify segmentation tasks. We evaluate and compare YOLOv3 with a MobileNetV2 backbone, YOLOv5, and SSD-Lite using the FUSeg dataset. Evaluation includes hyperparameter studies, 5-fold cross-validation, and feasibility experiments. Despite Faster R-CNN performing best, YOLOv5 demonstrates a favorable performance and accuracy tradeoff. The study highlights the importance of padding in wound localization and questions the correlation between mAP values and segmentation accuracy. Future directions include exploring end-to-end pipeline development and expanding evaluation to diverse skin wound datasets.

## Image Source

- Wang, C., Anisuzzaman, D.M., Williamson, V. et al. Fully automatic wound segmentation with deep convolutional neural networks. Sci Rep 10, 21897 (2020). https://doi.org/10.1038/s41598-020-78799-w