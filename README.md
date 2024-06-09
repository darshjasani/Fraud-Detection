# Fraud Prediction Models and Threshold Analysis

This repository contains a Jupyter Notebook for analyzing and predicting fraud using various machine learning models. The notebook demonstrates the application of logistic regression, Support Vector Classifier (SVC), and XGBoost models, and explores the impact of changing thresholds on recall and F1 score, which are crucial metrics in fraud detection to minimize false negatives.

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Dataset](#dataset)
5. [Modeling](#modeling)
6. [Evaluation](#evaluation)
7. [Results](#results)
8. [Contributing](#contributing)

## Introduction

Fraud detection is a critical application in various industries, aiming to identify and prevent fraudulent activities. This project focuses on building and evaluating machine learning models to enhance fraud detection accuracy and reduce false negatives by adjusting the decision threshold.

## Installation

To run this project locally, you will need to install the following dependencies:

```bash
pip install numpy pandas scikit-learn xgboost
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/fraud-prediction-and-threshold-analysis.git
cd fraud-prediction-and-threshold-analysis
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook fraud-prediction-and-threshold-analysis.ipynb
```

3. Execute the cells sequentially to reproduce the analysis and results.

## Dataset

The dataset used in this project is sourced from Kaggle's fraud detection dataset. It consists of two files:

- `fraudTrain.csv`
- `fraudTest.csv`

Ensure these files are placed in the appropriate directory before running the notebook.

## Modeling

The notebook includes the following steps for modeling:

1. **Data Loading and Preprocessing:** Loading the dataset and performing necessary preprocessing steps.
2. **Model Training:** Training logistic regression, SVC, and XGBoost models on the training dataset.
3. **Threshold Adjustment:** Changing the decision threshold to analyze its impact on recall and F1 score.

## Evaluation

The models are evaluated based on the following metrics:

- **Recall:** The ability of the model to identify all relevant instances (fraud cases).
- **F1 Score:** The balance between precision and recall, providing a single metric for evaluation.

## Results

The results section provides a comprehensive analysis of the model performance, highlighting the impact of threshold adjustments on recall and F1 score. Detailed plots and tables are included to visualize the findings.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before making any changes.
