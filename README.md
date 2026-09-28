![Python](https://img.shields.io/badge/python-3.11%2B-success)
[![License: BSD](https://img.shields.io/badge/license-BSD-success.svg)](https://github.com/solegalli/master-tree-ensemble-models/blob/main/LICENSE)
[![Powered by Train in Data](https://img.shields.io/badge/Powered%20By-TrainInData-orange.svg)](https://www.trainindata.com/)

# Master Tree Ensemble Models

Learn how decision trees and tree-based ensembles work under the hood, and how to train and tune them in practice. From single decision trees and random forests, to AdaBoost, gradient boosting, XGBoost, LightGBM and CatBoost.

This repository contains the practical notebooks for the **[Master Tree Ensemble Models](https://www.trainindata.com/p/master-tree-ensemble-models)** course. The examples cover classification, regression and ranking, using scikit-learn, XGBoost, LightGBM, and CatBoost.

**Course launch:** September 2026

**Status:** Actively maintained

[<img src="./logo.png" width="248" alt="Train in Data">](https://www.trainindata.com/p/master-tree-ensemble-models)

## What you will learn

- Understand how decision trees find splits, when to stop growing them, and how they produce predictions.
- Build ensembles with bagging and random forests, and understand why decorrelating trees works.
- Understand boosting, from AdaBoost to gradient boosting, and implement both from scratch.
- Learn what makes XGBoost, LightGBM and CatBoost fast and accurate: regularized losses, split-finding algorithms, histogram-based learning, GOSS, EFB, ordered boosting and more.
- Tune the key hyperparameters of each library and train models for classification, regression and ranking.
- Explore advanced topics like DART and gradient boosting with imbalanced data.

## Course contents

1. **Decision Trees** — [notebooks](01-decision-trees)
   - How decision trees work
   - Tree induction: selecting features and split values
   - Pruning and stopping tree growth
   - Training classification and regression trees

2. **Bagging and Random Forests** — [notebooks](02-random-forests)
   - Foundations of ensemble models
   - Bagging
   - Random forests and decorrelating the trees
   - Training classification and regression random forests

3. **Boosting** — [notebooks](03-boosting)
   - AdaBoost: intuition, algorithm and exponential loss
   - Gradient boosting: steepest descent, residuals and the algorithm
   - Training GBMs for classification and regression

4. **XGBoost** — [notebooks](04-xgboost)
   - Regularized loss function and split gain
   - Split finding: exact greedy and approximate algorithms
   - Weighted quantile sketch and sparsity-aware split finding
   - Feature importance
   - Hyperparameters, and the scikit-learn and native APIs
   - XGBoost for classification, regression and ranking

5. **LightGBM** — [notebooks](05-lightgbm)
   - Histogram-based split algorithm
   - Leaf-wise tree growth
   - Gradient-based One-Side Sampling (GOSS)
   - Exclusive Feature Bundling (EFB)
   - Hyperparameters
   - LightGBM for classification, regression and ranking

6. **CatBoost** — [notebooks](06-catboost)
   - Target statistics for categorical features
   - Ordered target statistics and feature combinations
   - Prediction shift and ordered boosting
   - Oblivious decision trees
   - Hyperparameters
   - CatBoost for classification, regression and ranking

## Getting started

Clone the repository (Python 3.11+ required), then set up a dedicated environment with **either** of the options below.

### Option 1: venv + pip

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

### Option 2: uv

```bash
uv sync
uv run jupyter notebook
```

Open the notebooks in numerical order.

## Course

For lectures, explanations, and the complete learning path, visit the [online course](https://www.trainindata.com/p/master-tree-ensemble-models).
