---
title: 'MVSplat360: Feed-Forward 360 Scene Synthesis from Sparse Views'
authors:
- Yuedong Chen
- Chuanxia Zheng
- Haofei Xu
- Bohan Zhuang
- Andrea Vedaldi
- Tat-Jen Cham
- Jianfei Cai
date: '2024-11-01'
publishDate: '2025-03-14T10:03:28.558798Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2411.04924
abstract: "We introduce MVSplat360, a feed-forward approach for 360deg novel view\
  \ synthesis (NVS) of diverse real-world scenes, using only sparse observations.\
  \ This setting is inherently ill-posed due to minimal overlap among input views\
  \ and insufficient visual information provided, making it challenging for conventional\
  \ methods to achieve high-quality results. Our MVSplat360 addresses this by effectively\
  \ combining geometry-aware 3D reconstruction with temporally consistent video generation.\
  \ Specifically, it refactors a feed-forward 3D Gaussian Splatting (3DGS) model to\
  \ render features directly into the latent space of a pre-trained Stable Video Diffusion\
  \ (SVD) model, where these features then act as pose and visual cues to guide the\
  \ denoising process and produce photorealistic 3D-consistent views. Our model is\
  \ end-to-end trainable and supports rendering arbitrary views with as few as 5 sparse\
  \ input views. To evaluate MVSplat360's performance, we introduce a new benchmark\
  \ using the challenging DL3DV-10K dataset, where MVSplat360 achieves superior visual\
  \ quality compared to state-of-the-art methods on wide-sweeping or even 360deg NVS\
  \ tasks. Experiments on the existing benchmark RealEstate10K also confirm the effectiveness\
  \ of our model. The video results are available on our project page: https://donydchen.github.io/mvsplat360."
tags:
- /unread
- Computer Science - Computer Vision and Pattern Recognition
- ZIPLAB
links:
- name: URL
  url: http://arxiv.org/abs/2411.04924
---
