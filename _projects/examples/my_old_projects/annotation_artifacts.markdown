---
layout: page
title: annotation artifacts
description: NLI models might not be making the right decisions for the right reasons.
img: /assets/img/artifacts0.png
importance: 5
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/artifacts.png' | relative_url }}" alt="" title="artifacts"/>
    </div>
</div>
<div class="caption">
    Annotation artifacts for different NLI labels.
</div>

We show that, in a significant portion of Natural Language Inference data, the annotation protocol leaves clues that make it possible to identify the label by looking only at the hypothesis, without observing the premise. Specifically, we show that a simple text categorization model can correctly classify the hypothesis alone in about 67% of SNLI (Bowman et. al, 2015) and 53% of MultiNLI (Williams et. al, 2017).

[Our paper](https://aclanthology.org/N18-2017/) presented at NAACL 2018:
```bib
@inproceedings{gururangan-etal-2018-annotation,
    title = "Annotation Artifacts in Natural Language Inference Data",
    author = "Gururangan, Suchin  and Swayamdipta, Swabha  and Levy, Omer  and
      Schwartz, Roy  and Bowman, Samuel  and Smith, Noah A.",
    booktitle = "Proceedings of the 2018 Conference of the NAACL-HLT, Volume 2 (Short Papers)",
    month = jun,
    year = "2018",
    address = "New Orleans, Louisiana",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/N18-2017",
    doi = "10.18653/v1/N18-2017",
    pages = "107--112",
}
```
