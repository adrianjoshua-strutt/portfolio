---
layout: post
title: "Medical Imaging Pre-Processing Pipelin"
thumbnail: "../assets/images/pipeline.png"
categories:
  - university
tags:
  - university
---

## TL;DR

- Color correction and pose estimation for medical images
- Proposed preprocessing: badge with ColorChecker and ArUco markers
- Colorchecker outperforms traditional methods
- Good distance estimation; rotation needs improvement
- Future work: optimize badge, integrate skin colors, assess deployment speed

## Abstract

Medical imaging plays a crucial role in diagnostic and therapeutic decision-making, yet its traditional handling within healthcare facilities can be costly and burdensome for both providers and patients. To alleviate this, there's a growing trend towards capturing and assessing medical images in non-clinical settings, such as patients' homes, using mobile devices. However, this introduces challenges related to color constancy and irregular camera angles and distances, potentially impacting diagnosis accuracy and image perception. In this context, we propose a robust pre-processing pipeline utilizing a badge comprising a Macbeth ColorChecker for color correction and ArUco markers for determining camera position and angle. We evaluate the effectiveness of colorchecker methods against traditional approaches under varying illumination conditions and assess different pose estimation algorithms. Our results indicate that color correction using colorcheckers significantly outperforms classic methods, with promising feasibility even without spectrophotometer optimization. Distance estimation yielded satisfactory results, while rotation estimation showed potential with room for improvement. Future work may explore optimizing badge size and assessing additional factors like skin color integration for enhanced medical imaging performance.
