---
layout: page
title: dataset cartography
description: Visualize datasets with respect to models.
img: /assets/img/SNLI_RoBERTa.png
importance: 1
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/SNLI_RoBERTa.png' | relative_url }}" alt="" title="SNLI-RoBERTa"/>
    </div>
</div>
<div class="caption">
    SNLI data map with respect to a RoBERTa model.
</div>

An automatic approach to study different regions in a dataset, as a side-effect of training a model.
Data maps provide point-wise estimates for individual data instances, based on the ease of a model to learn them.

Check out Elior Cohen's [wonderful blogpost](https://towardsdatascience.com/data-maps-datasets-can-be-distilled-too-1991c3c260d6) about [our paper](https://arxiv.org/abs/2009.10795).

```bib
@inproceedings{swayamdipta2020dataset,
      title={Dataset Cartography: Mapping and Diagnosing Datasets with Training Dynamics},
      author={Swabha Swayamdipta and Roy Schwartz and Nicholas Lourie and Yizhong Wang and Hannaneh Hajishirzi and Noah A. Smith and Yejin Choi},
      year={2020},
      url={https://arxiv.org/abs/2009.10795},
      booktitle={EMNLP}
}
```
