---
title: "Understanding Knowledge Distillation in Non-autoregressive Machine Translation"
collection: arxiv
permalink: /publication/understand_distillation
excerpt: "Chunting Zhou^, **Jiatao Gu**^, Graham Neubig"
date: 2019-11-07
venue: 'arxiv.org Pre-print'
---

![png](/images/self_training.jpg)<br>
**Abstract** <br>
Non-autoregressive machine translation (NAT) systems predict a sequence of output tokens in parallel, achieving substantial improvements in generation speed compared to autoregressive models. Existing NAT models usually rely on the technique of knowledge distillation, which creates the training data from a pretrained autoregressive model for better performance. Knowledge distillation is empirically useful, leading to large gains in accuracy for NAT models, but the reason for this success has, as of yet, been unclear. In this paper, we first design systematic experiments to investigate why knowledge distillation is crucial to NAT training. We find that knowledge distillation can reduce the complexity of data sets and help NAT to model the variations in the output data. Furthermore, a strong correlation is observed between the capacity of an NAT model and the optimal complexity of the distilled data for the best translation quality. Based on these findings, we further propose several approaches that can alter the complexity of data sets to improve the performance of NAT models. We achieve the state-of-the-art performance for the NAT-based models, and close the gap with the autoregressive baseline on WMT14 En-De benchmark.

[[paper]](https://arxiv.org/pdf/1911.02727.pdf) [code]

Please cite as:
```bibtex
@article{zhou2019understanding,
  title={Understanding Knowledge Distillation in Non-autoregressive Machine Translation},
  author={Zhou, Chunting and Gu, Jiatao and Neubig, Graham},
  journal={arXiv preprint arXiv:1911.02727},
  year={2019}
}
```