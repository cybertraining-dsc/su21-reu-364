---
date: 2021-06-16
title: "Project: Hand Tracking with AI"
linkTitle: "Hand Tracking"
tags: ["project", "reu", "ai", "object recognition", "image processing", "computer vision"]
description: "In this project we study the ability of an AI to recognize letters from the American Sign Language alphabet."
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

In this project we study the ability of an AI to recognize letters from the American Sign Language alphabet.

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** ai, object recognition, image processing, computer vision, american sign language. 

## 1. Introduction

Object detection and feature selection are essential tasks in computer vision and have been approached from various perspectives over the past few decades [1]. The brain uses object recognition to solve an inverse problem: one where (surface properties, shapes, and arrangements of objects) need to be inferred from the perceived outcome of the image formation process [3].Visual object recognition as a neural substrate in humans was revealed by neuropsychological studies. There are specific brain regions that cause object recognition, yet we still do not understand how the brain achieves this remarkable behavior [2]. Human beings rely and rapidly5 recognize objects despite considerable retinal image transformations arising from changes in lighting, image size, position, and viewing angle [2].

A gesture is a form of non verbal communication done with positions and movements of the hand, arms, body parts, hand shapes, movements of the lips or face [4]. One of the key differences of hand gestures is it allows communication over a long distance [5]. American Sign Language (ASL) is the formal language that has the same lingual properties as oral languages commonly used by deaf people as a way of communication [6]. ASL typically is formed by the finger, hand, and arm positioning and can contain static and dynamic movement or a combination of both to communicate words and meanings to another [7]. Communication with other people can be very difficult using this as people are not typically willing to learn sign language [7].

In this paper we consider the problem of detecting and understanding American Sign Language, we test a computers ability to recognize and translate in real time the ASL alphabet. As advancements in technology increase there are more improvements to 2D methods of hand detection and tracking ability. Commonly these methods are visual-based methods, using color, shape, and edge to detect and follow the hand [8]. While there are issues to these technologies like inconsitant lighting conditions, non-hand color similarity, and varying viewpoints can decrease a computers ability to recognitize the hand and its positioning.

- [X] Find liturature about image processing aand object recognition.
- [X] Analyze liturature & explain how this relates.

## 2. Data Sets

- [X] Datasets can be huge and GitHub has lmited space. Only very small datasets should be stored in GitHub. 
  However, if the data is publicly available your program must contain a download function instead that you customize. 
  Write it using pythons 'request'

![Figure 1](https://github.com/cybertraining-dsc/su21-reu-364/raw/main/project/images/hand b dataset.png)

**Figure 1:** Dataset of hands doing different alphabet letters in ASL [^5].

## 3. Using Images

- [ ] Place cool image into projects images in my directory (data set of its ability to be accurate).
- [X] Correct the following link, replace the fa with su, and the numbers to my reu numbers, change chart.png to file name.
- [ ] If the image has been copied, you must use a reference such as shown in the Figure 1 caption.

![Figure 2](https://github.com/cybertraining-dsc/su21-reu-364/raw/main/project/images/.png)

**Figure 2:** Images can be included in the report, but if they are copied you must cite them.

## 5. Example of an AI algorithm with Hand Tracking

OpenCV

## 6. Methodology

In this research we built the model using a convolution neural network (CNN) which allows the model to retrieve the images 

## 7. Benchmark

Your project must include a benchmark. The easiest is to use cloudmesh-common [^2]

## 8. Conclusion

A convincing but not fake conclusion should summarize what the conclusion of the project is.

## 9. Acknowledgments

We thank Carlos Theran (Florida A & M University) for advising, guidance, and resources used in the research; We thank Yohn Jairo (Florida A & M University) for guidance and aid on the research report; We thank Gregor von Laszewki (Florida A & M University) for advice and commenting on the code and report; We thank the Polk State LSAMP Program for aid in obtaining this opportunity. We thank Florida A & M University for funding this research.

## 10. References


[^1]: Pan, T.-Y., Zhang, C., Li, Y., Hu, H., Xuan, D., Changpinyo, S., Gong, B., &amp; Chao, W.-L. (2021, July 5). On Model Calibration for Long-Tailed Object Detection and Instance Segmentation. arXiv.org.
      https://arxiv.org/abs/2107.02170. 

[^2]: Wardle, S. G., & Baker, C. (2020). Recent advances in understanding object recognition in the human brain: Deep neural networks, temporal dynamics, and context. F1000Research. F1000 Research Ltd.
      <https://doi.org/10.12688/f1000research.22296.1>

[^3]: Wardle, S. G., & Baker, C. (2020). Recent advances in understanding object recognition in the human brain: Deep neural networks, temporal dynamics, and context. F1000Research. F1000 Research Ltd. 
      <https://doi.org/10.12688/f1000research.22296.1>

[^4]: Dabre, K., & Dholay, S. (2014). Machine learning model for sign language interpretation using webcam images. 2014 International Conference on Circuits, Systems, Communication and Information Technology Applications (CSCITA), 317-321.
      <https://ieeexplore.ieee.org/document/6839279>

[^5]: tecperson, Sign Language MNIST Drop-In Replacement for MNIST for Hand Gesture Recognition Tasks, [Kaggle] 
      <https://www.kaggle.com/datamunge/sign-language-mnist>

[^6]: U.S. Department of Health and Human Services. (n.d.). American Sign Language. National Institute of Deafness and Other Communication Disorders.
      <https://www.nidcd.nih.gov/health/american-sign-language>

[^7]: A. Rahagiyanto, A. Basuki, R. Sigit, A. Anwar and M. Zikky, "Hand Gesture Classification for Sign Language Using Artificial Neural Network," 2017 21st International Computer Science and Engineering Conference (ICSEC), 2017, pp. 1-5, 
      <doi: 10.1109/ICSEC.2017.8443898>

[^8]: Jiayi Wang, Franziska Mueller, Florian Bernard, Suzanne Sorli, Oleksandr Sotnychenko, Neng Qian, Miguel A. Otaduy, Dan Casas, and Christian Theobalt. 2020. RGB2Hands: real-time tracking of 3D hand interactions from monocular RGB video. ACM Trans. Graph. 39, 6, Article 218 (December 2020), 16 pages.
      <https://doi.org/10.1145/3414685.3417852>
