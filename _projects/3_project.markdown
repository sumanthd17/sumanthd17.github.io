---
layout: page
title: don't stop pretraining
description: Get more out of pretrained LMs by continuing to pretrain them in the domain or task of interest.
img: /assets/img/domains.png
importance: 3
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/domains.png' | relative_url }}" alt="" title="domains"/>
    </div>
</div>
<div class="caption">
    An illustration of data distributions. Task data is comprised of an observable task distribution, usually non-randomly sampled from a wider distribution (light grey ellipsis) within an even larger target domain, which is not necessarily one of the domains included in the original LM pretraining domain – though overlap is possible. We explore the benefits of continued pretraining on data from the task distribution and the domain distribution.
</div>

We present a study across four domains (biomedical and computer science publications, news, and reviews) and eight classification tasks, showing that a second phase of pretraining in-domain (domain-adaptive pretraining) leads to performance gains, under both high- and low-resource settings. Moreover, adapting to the task’s unlabeled data (task-adaptive pretraining) improves performance even after domain-adaptive pretraining. Finally, we show that adapting to a task corpus augmented using simple data selection strategies is an effective alternative, especially when resources for domain-adaptive pretraining might be unavailable.

[Our paper](https://aclanthology.org/2020.acl-main.740/) was nominated as a honorable mention for the best paper award at ACL 2020.
```bib
@inproceedings{gururangan-etal-2020-dont,
    title = "Don{'}t Stop Pretraining: Adapt Language Models to Domains and Tasks",
    author = "Gururangan, Suchin  and Marasovi{\'c}, Ana  and Swayamdipta, Swabha  and
      Lo, Kyle  and Beltagy, Iz  and Downey, Doug  and Smith, Noah A.",
    booktitle = "Proc. of the 58th Meeting of the Association for Computational Linguistics",
    month = jul,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2020.acl-main.740",
    doi = "10.18653/v1/2020.acl-main.740",
    pages = "8342--8360",
}
```
