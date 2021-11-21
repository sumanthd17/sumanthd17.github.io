---
layout: page
title: G-Daug and Common Sense
description: Generate data for improved performance on common sense benchmarks.
img: assets/img/gdaug.png
importance: 4
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/gdaug.png' | relative_url }}" alt="" title="gdaug"/>
    </div>
</div>
<div class="caption">
    Human curated vs. machine generated WinoGrad schema examples.
</div>

A simple approach to generate synthetic examples using pretrained language models (GPT2, finetuned on the task corpus), and selecting the most informative and diverse set of examples for data augmentation.

If building on [our project](https://gdaugc.apps.allenai.org/), please cite [our work](https://aclanthology.org/2020.findings-emnlp.90/):
```bibtex
@inproceedings{Yang2020GDAug,
  title={G-DAUG: Generative Data Augmentation for Commonsense Reasoning},
  author={Yiben Yang and Chaitanya Malaviya and Jared Fernandez and Swabha Swayamdipta and Ronan Le Bras and J. Wang and Chandra Bhagavatula and Yejin Choi and Doug Downey},
  booktitle={Findings of EMNLP},
  year={2020},
  url={https://arxiv.org/abs/2004.11546}
}
```
