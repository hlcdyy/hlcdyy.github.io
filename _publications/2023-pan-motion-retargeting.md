---
title: "Pose-aware Attention Network for Flexible Motion Retargeting by Body Part"
collection: publications
permalink: /publication/2023-pan-motion-retargeting
excerpt: ''
date: 2023
venue: 'IEEE TRANSACTIONS ON VISUALIZATION AND COMPUTER GRAPHICS'
paperurl: 'https://hlcdyy.github.io/pan-motion-retargeting/'
citation: 'Lei Hu, Zihao Zhang, Chongyang Zhong, Boyuan Jiang, and Shihong Xia. "Pose-Aware Attention Network for Flexible Motion Retargeting by Body Part." IEEE Transactions on Visualization and Computer Graphics (2023).'
---
Motion retargeting is a fundamental problem in computer graphics and computer vision. Existing approaches usually have many strict requirements, such as the source-target skeletons needing to have the same number of joints or share the same topology. To tackle this problem, we note that skeletons with different structure may have some common body parts despite the differences in joint numbers. Following this observation, we propose a novel, flexible motion retargeting framework. The key idea of our method is to regard the body part as the basic retargeting unit rather than directly retargeting the whole body motion. To enhance the spatial modeling capability of the motion encoder, we introduce a pose-aware attention network (PAN) in the motion encoding phase. The PAN is pose-aware since it can dynamically predict the joint weights within each body part based on the input pose, and then construct a shared latent space for each body part by feature pooling. Extensive experiments show that our approach can generate better motion retargeting results both qualitatively and quantitatively than state-of-the-art methods. Moreover, we also show that our framework can generate reasonable results even for a more challenging retargeting scenario, like retargeting between bipedal and quadrupedal skeletons because of the body part retargeting strategy and PAN.

[Download paper here](https://ieeexplore.ieee.org/document/10129844)

Recommended citation: Lei Hu, Zihao Zhang, Chongyang Zhong, Boyuan Jiang, and Shihong Xia. "Pose-Aware Attention Network for Flexible Motion Retargeting by Body Part." IEEE Transactions on Visualization and Computer Graphics (2023).
