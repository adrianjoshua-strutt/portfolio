---
layout: post
title: "Development of a Robust Pre-Processing Pipeline for Medical Imaging in Non-Standardized Home Environments"
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

The utilization of mobile devices for capturing medical images outside clinical settings has surged, aiming to alleviate the burden on healthcare systems. However, this introduces challenges related to color consistency and accurate camera positioning. In this study, we propose a robust preprocessing pipeline employing a badge featuring a Macbeth ColorChecker for color correction and ArUco markers for pose estimation. We evaluate the effectiveness of colorchecker methods against traditional approaches under varying illumination conditions and assess different pose estimation algorithms. Our results indicate that color correction using colorcheckers significantly outperforms classic methods, with promising feasibility even without spectrophotometer optimization. Distance estimation yielded satisfactory results, while rotation estimation showed potential with room for improvement. Future work may explore optimizing badge size and assessing additional factors like skin color integration for enhanced medical imaging performance.
