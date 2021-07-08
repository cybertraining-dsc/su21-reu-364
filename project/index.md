---
date: 2021-06-16
title: "Project: Hand Tracking with AI"
linkTitle: "Hand Tracking"
tags: ["project", "reu", "ai", "object recognition", "image processing", "computer vision"]
description: "In this project we study the ability of an AI to recognize and track hand positions then recognize letters from the American Sign Language alphabet."
author: David, Umanzor
github_url: https://github.com/cybertraining-dsc/su21-reu-364/edit/main/project/index.md
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
---

[![Check Report](https://github.com/cybertraining-dsc/su21-reu-364/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-364/actions)
[![Status](https://github.com/cybertraining-dsc/su21-reu-364/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-364/actions)
Status: draft, Type: Project


David Umanzor, [su21-reu-364](https://github.com/cybertraining-dsc/su21-reu-364), [Edit](https://github.com/cybertraining-dsc/su21-reu-364/blob/main/project/index.md)

{{% pageinfo %}}

## Abstract

In this project we study the ability of an AI to recognize and track hand positions then recognize letters from the American Sign Language alphabet.

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** ai, object recognition, image processing, computer vision, hand tracking, american sign language. 

## 1. Introduction

Object detection and feature selection are essential tasks in computer vision and have
been approached from various perspectives over the past few decades [1]. The brain uses object recognition to solve an inverse problem: one where (surface properties, shapes, and arrangements of objects) need to be inferred from the perceived outcome of the image formation process [3].
Visual object recognition as a neural substrate in humans was revealed by neuropsychological studies. There are specific brain regions2,3, yet we still do not 
understand how the brain achieves this remarkable behavior [2]. Human beings rely and rapidly5 recognize objects despite considerable retinal image transformations arising from changes in lighting, image size, position, and viewing angle [2].

A gesture is a form of non verbal communication done with positions and movements of the hand, arms, body parts, hand shapes, movements of the lips or face [4].

In this paper we consider the problem of detecting and localizing generic objects from
categories such as people or cars in moving images and the amount of resources it takes
to complete the process.

- [X] Find liturature about image processing aand object recognition.
- [X] Analyze liturature & explain how this relates.

## 2. Data Sets

- [X] Collect image sets for the AI to recognize.
- [X] What do these data sets specify.
- [X] What are the challenges with hand tracking? Volatile illumination conditions, occlusion, non-hand color similarity, and varying viewpoints.
- [X] Datasets can be huge and GitHub has lmited space. Only very small datasets should be stored in GitHub. 
  However, if the data is publicly available your program must contain a download function instead that you customize. 
  Write it using pythons 'request' 

![Figure 1](https://github.com/cybertraining-dsc/su21-reu-364/raw/main/project/images/amer_sign2.png)

**Figure 1:** Dataset of hands doing different alphabet letters in ASL [^5].

## 3. Using Images

- [X] Place cool image into projects images in my directory (data set of its ability to be accurate).
- [X] Correct the following link, replace the fa with su, and the numbers to my reu numbers, change chart.png to file name.
- [X] If the image has been copied, you must use a reference such as shown in the Figure 1 caption.

![Figure 2](https://github.com/cybertraining-dsc/su21-reu-364/raw/main/project/images/hand_tracking_test.png)

**Figure 2:** Images can be included in the report, but if they are copied you must cite them.

## 5. Example of an AI algorithm with Object Recognition

- [X] Identify the concrete data set that will be used.
- [X] Identify the conrete algorithm that completes the image processing for Hand Tracking.
- [X] Write the program.
- [X] Verify that it works.

## 6. Benchmark

Your project must include a benchmark. The easiest is to use cloudmesh-common [^2]

## 6. Conclusion

A convincing but not fake conclusion should summarize what the conclusion of the project is.

## 8. Acknowledgments

Please add acknowledgments to all that contributed or helped on this project.

- [ ] Gregor von Laszewski
- [ ] 

## 9. References


[^1]: Pan, T.-Y., Zhang, C., Li, Y., Hu, H., Xuan, D., Changpinyo, S., Gong, B., &amp; Chao, W.-L. (2021, July 5). On Model Calibration for Long-Tailed Object Detection and Instance Segmentation. arXiv.org.
      https://arxiv.org/abs/2107.02170. 
      
[^2]: Wardle, S. G., & Baker, C. (2020). Recent advances in understanding object recognition in the human brain: Deep neural networks, temporal dynamics, and context. F1000Research. F1000 Research Ltd.
      <https://doi.org/10.12688/f1000research.22296.1>


      
[^4]: K. Dabre and S. Dholay, "Machine learning model for sign language interpretation using webcam images," 2014 International Conference on Circuits, Systems, Communication and Information Technology Applications (CSCITA), 2014, pp. 317-321, doi: 10.1109/CSCITA.2014.6839279.

[^5]: tecperson, Sign Language MNIST Drop-In Replacement for MNIST for Hand Gesture Recognition Tasks, [Kaggle] 
      <https://www.kaggle.com/datamunge/sign-language-mnist>

