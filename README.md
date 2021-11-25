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
