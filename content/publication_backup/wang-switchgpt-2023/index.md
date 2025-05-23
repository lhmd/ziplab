---
title: 'SwitchGPT: Adapting Large Language Models for Non-Text Outputs'
authors:
- Xinyu Wang
- Bohan Zhuang
- Qi Wu
date: '2023-09-01'
publishDate: '2025-03-14T12:48:48.074372Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2309.07623
abstract: Large Language Models (LLMs), primarily trained on text-based datasets,
  exhibit exceptional proficiencies in understanding and executing complex linguistic
  instructions via text outputs. However, they falter when requests to generate non-text
  ones. Concurrently, modality conversion models, such as text-to-image, despite generating
  high-quality images, suffer from a lack of extensive textual pretraining. As a result,
  these models are only capable of accommodating specific image descriptions rather
  than comprehending more complex instructions. To bridge this gap, we propose a novel
  approach, methodname, from a modality conversion perspective that evolves a text-based
  LLM into a multi-modal one. We specifically employ a minimal dataset to instruct
  LLMs to recognize the intended output modality as directed by the instructions.
  Consequently, the adapted LLM can effectively summon various off-the-shelf modality
  conversion models from the model zoos to generate non-text responses. This circumvents
  the necessity for complicated pretraining that typically requires immense quantities
  of paired multi-modal data, while simultaneously inheriting the extensive knowledge
  of LLMs and the ability of high-quality generative models. To evaluate and compare
  the adapted multi-modal LLM with its traditional counterparts, we have constructed
  a multi-modal instruction benchmark that solicits diverse modality outputs. The
  experiment results reveal that, with minimal training, LLMs can be conveniently
  adapted to comprehend requests for non-text responses, thus achieving higher flexibility
  in multi-modal scenarios. Code and data will be made available at https://github.com/xinke-wang/SwitchGPT.
links:
- name: URL
  url: http://arxiv.org/abs/2309.07623
---
