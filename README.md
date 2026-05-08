# INFO 371 Data Mining Portfolio

This repository collects coursework from INFO 371: Data Mining Applications. The notebooks show a progression from exploratory prediction objectives and KNN classification to tree-based models, text classification, and neural network image classification.

## Portfolio Overview

| Work | Data context | Data mining focus | Status |
| --- | --- | --- | --- |
| Assignment 1: Stack Overflow + KNN | Stack Overflow developer survey and a small exam outcome dataset | Prediction framing, feature selection, KNN classification | Reproducible with included data |
| Assignment 2: NBA Outcomes | 2023-2024 NBA game results | Feature engineering, decision trees, random forests, grid search | Reproducible with included data |
| Assignment 3: IMDB Sentiment | 5,000 IMDB movie reviews | Text vectorization and sentiment classification | Notebook included; dataset not included |
| Assignment 4: Butterfly Classification | HDF5 image dataset with butterfly images and labels | Dense neural networks and CNN image classification | Reproducible with included data |
| Project Proposal | Smartphone usage, sleep, stress, and productivity dataset | Proposed regression/classification project design | Proposal included; dataset not included |

## Repository Layout

```text
assignments/
  assignment-1-stackoverflow-knn/
  assignment-2-nba-outcomes/
  assignment-3-imdb-sentiment/
  assignment-4-butterfly-classification/
  project-proposal-smartphone-productivity/
```

Each assignment folder contains the notebook, a short README, and a `data/` folder when the required dataset is available.

## Running the Notebooks

Install the dependencies, then open the notebooks with Jupyter:

```bash
pip install -r requirements.txt
jupyter notebook
```

Large datasets are tracked with Git LFS. After cloning, run:

```bash
git lfs pull
```

