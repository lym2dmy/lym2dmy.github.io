---
layout: post
title:  "Wind turbine blade surface inspection based on deep learning and UAV-taken images"
date:   2021-1-1 22:52:11
categories: CE
tags: papers wind-turbine deep-learning UAV
excerpt: Wind turbine blade surface inspection based on deep learning and UAV-taken images.
mathjax: true
---

# Reference

> Xu, D., Wen, C. and Liu, J., 2019. Wind turbine blade surface inspection based on deep learning and UAV-taken images. Journal of Renewable and Sustainable Energy, 11(5), p.053305.

[https://doi.org/10.1063/1.5113532](https://doi.org/10.1063/1.5113532)

Submitted: 04 June 2019 . Accepted: 24 September 2019 . Published Online: 10 October 2019

# Abstract
> As a key component of wind turbines (WTs), the blade conditions are related to the WT normal operation and the WT blade inspection is a significant task. Most studies of WT blade inspection focus attention on acquired sensor signal processing; however, there exist problems of stability, sensor installation, and data storage and processing. Onsite visual surface inspection is still the most common inspection method, but it is inefficient and requires a long downtime. Aimed at solving the above issues, a novel blade inspection method based on deep learning and unmanned aerial vehicles is proposed. Since common defect types are visible, the inspection problem is regarded as an image recognition problem. Three convolutional neural networks are trained by using the constructed dataset for image recognition, and the F1-score is applied to evaluate the models. The VGG-11 model is chosen for the final model due to its best performance. Then, the alternating direction method of multipliers algorithm is employed to compress the model to reduce the requirements on hardware devices. The blind area of the WT can be reduced, the efficiency of subsequent maintenance can be improved, maintenance costs can be reduced, and the economic performance can be increased. Finally, a comparison experiment of different inspection methods is carried out to demonstrate the proposed advantages.

# Comments
1. Since common defect types are visible, the inspection problem is regarded as an image recognition problem.
2. Generally, this paper contains **a whole flow of the CNN algorithm**, **which is worthy to learn the details**.
3. CNNs are trained and F1-score is used to assess the models.
4. The dataset contains 25,773 images with 5 common defect conditions, which are navigation paint off, gelcoat off, surface erosion, oil stain, and normal conditions.
5. The Mavic2 Pro UAVs were deployed to take the WT blade images.
6. The camera has a resolution of 5472x3684. 
7. Three CNN models are tested for the recognition task using TensorFlow, including LeNet-5, AlexNet, and VGG-11.
8. In order to reduce the computational load and model storage require- ments ofCNNs simultaneously, a significant amount ofprevious work is dedicated to model compression methods. Zhang et al. presented a systematic frame- work of model compression to provide theoretical support, they adopted the **alternating direction method ofmultipliers (ADMM)** for systematic weight pruning, and the experimental comparison shows that the method has better compression ability than other weight pruning methods without affecting the model performance.


# Questions
1. The method combined UAV-based image acquisition and deep learning is not the first time to proposed. The paper tried to detect five conditions (four defect conditions, one normal condition). What's the novelty of this paper?
