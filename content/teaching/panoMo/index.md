---
title: panoMosaics
summary: Enhanced Visualization Interface for AR Object Detection
date: 2023-04-24
type: docs
math: false
tags:
  - Python
  - Computer Vision
  - Object Detection
  - Augmented Reality
image:
  caption: 'Panoramic Stitching Example'
---

You can find the source code at this [Project Repository](https://github.com/egm68/panoramic-mosaics). Additionally, if you'd like to read about the results you can do so at this [Paper Link](https://github.com/egm68/panoramic-mosaics/blob/main/panoMosaics_report.pdf).

## Brief Description

Traditional methods of visualizing and evaluating the output of object detection models are limited to capturing objects within a single frame and timestep, and thus fail to capture the temporal and spatial context that is often necessary for various domain applications. We propose panoMosaics, an enhanced approach for visualizing object detection that maximizes user understanding of model performance. The proposed visualization harmonizes time-variant features in a panoramic mosaic display that expands the field of view and facilitates object detection model debugging through augmented bounding boxes. We enhance the standard bounding box visualization by leveraging object trails with different colors and gradients to convey object positions over multiple timesteps. We also present a faster algorithm for panorama stitching than previous work. We demonstrate the effectiveness of panoMosaics via a use case by contrasting our approach against multiple baselines. The panoMosaics library is pip-installable and available at https://github.com/egm68/panoramic-mosaics.