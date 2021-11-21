---
layout: page
title: Syntactic Scaffolds
description: Use a small amount to syntax to do better on semantics.
img: /assets/img/scaffold.png
importance: 3
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/scaffold.png' | relative_url }}" alt="" title="scaffold"/>
    </div>
</div>
<div class="caption">
    Model architecture for jointly training syntax and semantics.
</div>

Syntactic scaffolds avoid expensive syntactic processing at runtime, only making use of a treebank during training, through a multitask objective. We improve over strong baselines on PropBank semantics, frame semantics, and coreference resolution, achieving competitive performance on all three tasks.


[Our paper](https://aclanthology.org/D18-1412/) was presented at EMNLP 2018:
```bib
@inproceedings{Swayamdipta2018SyntacticSF,
  title={Syntactic Scaffolds for Semantic Structures},
  author={Swabha Swayamdipta and Sam Thomson and Kenton Lee and Luke Zettlemoyer and Chris Dyer and Noah A. Smith},
  booktitle={EMNLP},
  year={2018},
  url={https://arxiv.org/abs/1808.10485}
}
```
