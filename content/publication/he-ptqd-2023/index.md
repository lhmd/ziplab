---
title: 'PTQD: Accurate Post-Training Quantization for Diffusion Models'
authors:
- Yefei He
- Luping Liu
- Jing Liu
- Weijia Wu
- Hong Zhou
- Bohan Zhuang
date: '2023-11-01'
publishDate: '2025-03-14T10:03:28.524446Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2305.10657
abstract: Diffusion models have recently dominated image synthesis tasks. However,
  the iterative denoising process is expensive in computations at inference time,
  making diffusion models less practical for low-latency and scalable real-world applications.
  Post-training quantization (PTQ) of diffusion models can significantly reduce the
  model size and accelerate the sampling process without re-training. Nonetheless,
  applying existing PTQ methods directly to low-bit diffusion models can significantly
  impair the quality of generated samples. Specifically, for each denoising step,
  quantization noise leads to deviations in the estimated mean and mismatches with
  the predetermined variance schedule. As the sampling process proceeds, the quantization
  noise may accumulate, resulting in a low signal-to-noise ratio (SNR) during the
  later denoising steps. To address these challenges, we propose a unified formulation
  for the quantization noise and diffusion perturbed noise in the quantized denoising
  process. Specifically, we first disentangle the quantization noise into its correlated
  and residual uncorrelated parts regarding its full-precision counterpart. The correlated
  part can be easily corrected by estimating the correlation coefficient. For the
  uncorrelated part, we subtract the bias from the quantized results to correct the
  mean deviation and calibrate the denoising variance schedule to absorb the excess
  variance resulting from quantization. Moreover, we introduce a mixed-precision scheme
  for selecting the optimal bitwidth for each denoising step. Extensive experiments
  demonstrate that our method outperforms previous post-training quantized diffusion
  models, with only a 0.06 increase in FID score compared to full-precision LDM-4
  on ImageNet 256x256, while saving 19.9x bit operations. Code is available at https://github.com/ziplab/PTQD.
tags:
- /unread
- Computer Science - Computer Vision and Pattern Recognition
- ZIPLAB
links:
- name: URL
  url: http://arxiv.org/abs/2305.10657
---
