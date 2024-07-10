

# Credit Card Fraud Detection

This repository contains a project for detecting fraudulent credit card transactions using machine learning. The dataset used for this project is sourced from [Kaggle's Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/discussion/373669).

### Dataset used: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/discussion/373669


## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Techniques to Handle Imbalanced Data](#techniques-to-handle-imbalanced-data)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Overview

Credit card fraud detection is crucial to prevent unauthorized transactions and protect customers. This project aims to build a machine learning model to classify transactions as fraudulent (1) or genuine (0).

## Dataset

The dataset contains 284,807 transactions, each with 30 features (V1 to V28) that are the principal components obtained through PCA, and two additional features (`Time` and `Amount`).

- **Time**: Seconds elapsed between each transaction and the first transaction.
- **Amount**: The transaction amount.
- **Class**: Response variable, 1 for fraud and 0 for genuine.

## Installation

To get started, clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
```


## Techniques to Handle Imbalanced Data
To address the imbalanced nature of the dataset, the following techniques can be used:

- Resampling Techniques: Oversampling the minority class or undersampling the majority class.
- Cost-Sensitive Learning: Modifying the loss function to assign more weight to the minority class.
- Ensemble Methods: Using multiple models and combining their predictions.
- Thresholding: Adjusting the decision threshold of the model.
- Generative Adversarial Networks (GANs): Creating synthetic examples of the minority class.
