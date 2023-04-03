# IMDB-WIKI-SbS: An Evaluation Dataset for Crowdsourced Pairwise Comparisons

## Overview

This is an official repository of the IMDB-WIKI-SbS dataset presented in [this paper](https://arxiv.org/abs/2110.14990).

```
└── data
    ├── crowd_labels.csv
    └── gt.csv
```
## Data Format

The `crowd_labels.csv` file contains the annotation. It is a comma-separated table containing information about the comparisons made by crowd performers:

- `left`. URL of the image positioned on the left side of the task's page.
- `right`. URL of the image positioned on the right side of the task's page.
- `label`. URL of the image of the older person according to the annotator's opinion.
- `performer`. Anonymized annotator's identifier.

The `gt.csv` file contatins the ground-truth information from the original IMDB-WIKI dataset. It is a comma-separated table with columns:
- `label`. Image url.
- `score`. The ground-truth age in years.

## Citation

Please cite the challenge results or dataset description as follows.

- Ustalov D., Pavlichenko N. [IMDB-WIKI-SbS: An Evaluation Dataset for Crowdsourced Pairwise Comparisons](https://goo.su/DwBUgR).

```bibtex
@article{DBLP:journals/corr/abs-2110-14990,
  author    = {Nikita Pavlichenko and
               Dmitry Ustalov},
  title     = {IMDB-WIKI-SbS: An Evaluation Dataset for Crowdsourced Pairwise Comparisons},
  journal   = {CoRR},
  volume    = {abs/2110.14990},
  year      = {2021},
  url       = {https://arxiv.org/abs/2110.14990},
  eprinttype = {arXiv},
  eprint    = {2110.14990},
  timestamp = {Tue, 02 Nov 2021 15:31:04 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-2110-14990.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```
