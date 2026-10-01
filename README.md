# Heart Disease Classification with Tree Ensembles

A machine-learning portfolio project comparing **Decision Tree**, **Random Forest**, and **XGBoost** classifiers on the Kaggle **Heart Failure Prediction** dataset.

## What this project demonstrates

- Python data work with **pandas** and **NumPy**
- categorical preprocessing with one-hot encoding
- train/validation experimentation
- manual hyperparameter analysis for tree-based models
- comparison of train and validation accuracy to inspect overfitting
- XGBoost training with an evaluation set and early stopping
- visualization with **matplotlib**

## Dataset

Public Kaggle dataset: `fedesoriano/heart-failure-prediction`.

The notebook downloads the dataset with `kagglehub`; the CSV does not need to be committed to this repository.

## Saved experiment results

| Model | Train accuracy | Validation accuracy |
|---|---:|---:|
| Decision Tree | 86.65% | 86.96% |
| Random Forest | 92.92% | **88.59%** |
| XGBoost | 93.19% | 85.33% |

The Random Forest produced the strongest validation accuracy in this experiment.

## Run locally

```bash
pip install -r requirements.txt
jupyter notebook heart_disease_tree_ensembles.ipynb
```

KaggleHub may require Kaggle authentication depending on the environment.

## Notes

This repository is a portfolio version of work originally developed in Google Colab. Personal Drive paths and local style-file dependencies were removed so the notebook is easier for other people to inspect and run.

This project is for learning and portfolio purposes and is **not** a medical diagnostic tool.
