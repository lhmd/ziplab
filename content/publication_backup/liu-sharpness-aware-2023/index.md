---
title: Sharpness-aware Quantization for Deep Neural Networks
authors:
- Jing Liu
- Jianfei Cai
- Bohan Zhuang
date: '2023-03-01'
publishDate: '2025-03-14T12:48:48.055089Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2111.12273
abstract: Network quantization is a dominant paradigm of model compression. However,
  the abrupt changes in quantized weights during training often lead to severe loss
  fluctuations and result in a sharp loss landscape, making the gradients unstable
  and thus degrading the performance. Recently, Sharpness-Aware Minimization (SAM)
  has been proposed to smooth the loss landscape and improve the generalization performance
  of the models. Nevertheless, directly applying SAM to the quantized models can lead
  to perturbation mismatch or diminishment issues, resulting in suboptimal performance.
  In this paper, we propose a novel method, dubbed Sharpness-Aware Quantization (SAQ),
  to explore the effect of SAM in model compression, particularly quantization for
  the first time. Specifically, we first provide a unified view of quantization and
  SAM by treating them as introducing quantization noises and adversarial perturbations
  to the model weights, respectively. According to whether the noise and perturbation
  terms depend on each other, SAQ can be formulated into three cases, which are analyzed
  and compared comprehensively. Furthermore, by introducing an efficient training
  strategy, SAQ only incurs a little additional training overhead compared with the
  default optimizer (e.g., SGD or AdamW). Extensive experiments on both convolutional
  neural networks and Transformers across various datasets (i.e., ImageNet, CIFAR-10/100,
  Oxford Flowers-102, Oxford-IIIT Pets) show that SAQ improves the generalization
  performance of the quantized models, yielding the SOTA results in uniform quantization.
  For example, on ImageNet, SAQ outperforms AdamW by 1.2% on the Top-1 accuracy for
  4-bit ViT-B/16. Our 4-bit ResNet-50 surpasses the previous SOTA method by 0.9% on
  the Top-1 accuracy.
links:
- name: URL
  url: http://arxiv.org/abs/2111.12273
---
