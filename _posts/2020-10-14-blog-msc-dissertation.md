---
title: 'An Attempt to Reduce the Number of Training Samples for Convolutional Neural Networks'
date: 2020-10-14
permalink: /posts/2020/10/msc-data-reduction/
tags:
  - Computer Vision
  - Data Reduction
  - Convolutional Neural Network
  - excerpt_separator: <!--more-->
  - toc: true
---
Training deep neural networks can be resources-consuming. The budget required is in- creasing with the size of the dataset. During the past ten years, many achievements are dedicated to accelerating the convergence speed with heuristic or theoretical training procedures. However, we still need the whole dataset to train the network and paying for a large dataset may not pay back well if we can use a smaller subset to achieve an acceptable performance. In order to reduce the number of training samples needed, we first adapted and evaluated three methods, Patterns by Ordered Projections (POP), En- hanced Global Density-based Instance Selection (EGDIS), and Curriculum Learning (CL), to reduce the size of two image datasets, CIFAR10 and CIFAR100, for the clas- sification task. Based on the analysis, we present our main contributions: improved CL and evaluated its two variations, the Weighted Curriculum Learning (WCL) and the Boundary based Weighted Curriculum Learning (BWCL). The WCL outperforms POP and EGDIS in terms of both classification accuracy and time complexity. Also, WCL and BWCL achieve comparable performance compared with CL while keeping a portion of hard examples. Besides, we proposed a trade-off framework for WCL to select a subset of samples according to the acceptable relative accuracy and the original datasets.

<iframe src="/files/pdf/msc_dissertation.pdf" width="100%" height="500" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>

You can download a PDF copy of my dissertation [here](/files/pdf/msc_dissertation.pdf).