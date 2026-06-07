---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate at UdeM/Mila, co-supervised by Eilif Muller and Irina Rish. I aim to understand the conditions under which models lose prior capabilities and gain new ones, in order to make them lifelong learners.

Classic notions of forgetting and plasticity do not apply directly to modern language models, so I study them through the models' own output distributions, connecting continual learning to test-time sampling. This work is preliminary; in recent work, [Failed Reasoning Traces Tell You What Is Fixable (But Not by Reading Them)](https://arxiv.org/abs/2606.05145), I show that a continually post-trained model's latent capability can be surfaced by contrasting it with its own base model, using only signatures of their logit distributions, with no training-time access, no weight space, and no hidden states; and conversely, the post-training method itself can be read off from the same signatures.

Previously, I have led work on benchmarking [prior coding knowledge conflicts](https://arxiv.org/abs/2507.12367), contributed to work on [continual pre‑training strategies](https://arxiv.org/abs/2508.01908), and explored [test‑time learning](https://openreview.net/forum?id=IsbtaJ3IrJ). Throughout all of these projects, the goal has been consistent: find ways to improve models over time and better evaluate them over time. I am currently exploring methods for continual posttraining. If you are working on similar things feel free to reach out.
