---
layout: page
title: aflite
description: Filter dataset instances with spurious biases.
img: /assets/img/synthetic-aflite.png
importance: 2
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/synthetic-aflite.png' | relative_url }}" alt="" title="AFLite"/>
    </div>
</div>
<div class="caption">
    Four sample biased datasets as input to AFLite (top). Blue and orange indicate two different classes. Only the original two dimensions are shown, not the bias features. For the dataset on the left, with the highest separation, we flip some labels at random, so even an RBF kernel cannot achieve perfect performance. AFLite makes the data more challenging for the models (bottom).
</div>

A detailed investigation into an algorithm which adversarially filters dataset biases, which are responsible for demonstration of human-level performance on language and vision benchmarks, while this performance degrades considerably on adversarial or out-of-distribution samples. AFLite offers a means to mitigate the prevalent overestimation of machine performance. It has been applied to [filtering social biases](https://arxiv.org/abs/2102.00086), and has been [replicated on multiple benchmarks using various models](https://jasonphang.com/files/advpaper.pdf).

[Our paper](http://proceedings.mlr.press/v119/bras20a/bras20a.pdf) was presented at ICML 2020.
```bib
@inproceedings{Bras2020AdversarialFO,
  title={Adversarial Filters of Dataset Biases},
  author={Ronan Le Bras and Swabha Swayamdipta and Chandra Bhagavatula and Rowan Zellers and Matthew E. Peters and A. Sabharwal and Yejin Choi},
  bibtex={ICML},
  year={2020},
  url={https://arxiv.org/abs/2002.04108}
}
```
