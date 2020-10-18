# Phonology2vec

Tools for analyzing and visualizing the phonologies of different languages using corpora written in IPA.

## Project Organization
------------

    │
    ├── README.md           
    ├── CHANGELOG.md        <- See keepachangelog.com
    ├── pyproject.toml      <- See PEP 518
    ├── poetry.lock         <- See Poetry documentation
    ├── tests               <- Scripts for testing
    ├── notebooks           <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │   └── fix_notebook_imports.py
    ├── references          <- Data dictionaries, manuals, and all other explanatory materials.
    ├── reports             <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures         <- Generated graphics and figures to be used in reporting
    └── phonology2vec
        ├── util.py         <- Shared functions and helpful file paths
        ├── make_dataset.py <- Scripts to download or generate data
        ├── pipeline.py     <- Data processing pipeline to be used in train.py and predict.py
        ├── train.py        <- Train model
        ├── predict.py      <- Make predictions using a trained model
        ├── visualize.py    <- Script to create exploratory and results-oriented visualizations
        ├── data
        │   ├── external    <- Data from third party sources.
        │   ├── interim     <- Intermediate data that has been transformed.
        │   ├── processed   <- The final, canonical data sets for modeling.
        │   └── raw         <- The original, immutable data dump.
        └── models          <- Trained and serialized models and model predictions
     


## Instructions

1. Download the dataset from here: https://www.kaggle.com/mrinalmanu/bible-verses-30-languages-ipa-annotated/

2. Place the following files in the data directory:

```
phonology2vec/data/raw/annotated_feature_DF.csv
phonology2vec/data/raw/IPA_DF.pkl
```

3. Run jupyter notebook(s)

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
