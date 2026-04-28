# Data Science Notebooks

This repository contains a collection of Jupyter Notebooks covering diverse data science, machine learning, and statistical topics. Technologies used throughout the notebooks include Python, PyTorch, scikit-learn, XGBoost, pandas, and other libraries for data analysis, modeling, and visualization.

---

## Notebooks Overview

### [CNN-transfer-learning.ipynb](./CNN-transfer-learning.ipynb)
**Deep Learning, PyTorch, CNN, Transfer Learning**

Builds a Convolutional Neural Network (CNN) from scratch for American Sign Language (ASL) recognition and applies transfer learning using the ResNet-50 architecture to improve performance. Utilizes PyTorch for all deep learning tasks.

---

### [EDA-practice.ipynb](./EDA-practice.ipynb)
**Exploratory Data Analysis, Python, pandas**

A hands-on notebook for performing typical exploratory data analysis (EDA) tasks using pandas, matplotlib, and seaborn to visualize and summarize datasets.

---

### [GMM-classifier.ipynb](./GMM-classifier.ipynb)
**Gaussian Mixture Models, scikit-learn**

Implements a Gaussian Mixture Model (GMM) classifier for unsupervised and semi-supervised learning problems, exploring how probabilistic models can be used for classification tasks.

---

### [LSH-group.ipynb](./LSH-group.ipynb)
**Locality Sensitive Hashing (LSH), Text Mining, scikit-learn, NumPy**

Builds a full pipeline for fast document similarity search using Locality Sensitive Hashing (LSH) on text data (20 Newsgroups dataset). Includes data preprocessing, TF-IDF vectorization, hash signature generation, and efficient retrieval evaluation.

---

### [ROC_AUC.ipynb](./ROC_AUC.ipynb)
**Model Evaluation, Python, scikit-learn, matplotlib**

Demonstrates how to compute and plot the Receiver Operating Characteristic (ROC) Curve and calculate the Area Under the Curve (AUC) from scratch, and validates results against scikit-learn.

---

### [churn-analysis.ipynb](./churn-analysis.ipynb)
**Classification, Random Forest, scikit-learn, pandas, SMOTE**

Performs end-to-end Telco customer churn analysis, including preprocessing, feature engineering, EDA, and model training/evaluation with Random Forests in Python using scikit-learn and pandas.

---

### [data-analysis-sleep-efficiency.ipynb](./data-analysis-sleep-efficiency.ipynb)
**Statistical Analysis, Python, statsmodels, pandas**

Analyzes sleep efficiency and relevant factors using a real-world dataset, leveraging Python libraries such as statsmodels and pandas for regression analysis and hypothesis testing.

---

### [data-size-analysis.ipynb](./data-size-analysis.ipynb)
**Statistical Distributions, Python, scipy.stats, Matplotlib**

Investigates the distributions of variables in two datasets (health and wine quality) and applies goodness-of-fit tests (Kolmogorov–Smirnov) using scipy.stats to compare empirical and theoretical distributions.

---

### [ensemble-model-group.ipynb](./ensemble-model-group.ipynb)
**Ensemble Learning, Transfer Learning, PyTorch, scikit-learn, Random Forest**

Explores ASL classification using transfer learning with multiple pre-trained image models (ResNet, EfficientNet, DenseNet) for feature extraction. Models are stacked and a Random Forest classifier is used as the meta-learner for final predictions.

---

### [logistic-regression.ipynb](./logistic-regression.ipynb)
**Logistic Regression, Feature Engineering, Python, scikit-learn**

Covers logistic regression applied to heart disease prediction, including polynomial and spline transformations, model evaluation (ROC, AUC), and cross-validation—all implemented in Python with scikit-learn.

---

### [podcast_timestamp_classification.ipynb](./podcast_timestamp_classification.ipynb)
**Audio Processing, Speaker Classification, PyTorch, librosa**

Implements an audio processing pipeline for classifying podcast speakers (male vs. female), with feature extraction via librosa (MFCC, pitch, spectral centroid) and modeling using an LSTM neural network with PyTorch. Includes semi-supervised learning techniques.

---

### [recommendation-system-Amazon-books.ipynb](./recommendation-system-Amazon-books.ipynb)
**Recommender Systems, Python, scikit-surprise, pandas**

Constructs recommender systems for Amazon book ratings using collaborative and content-based approaches. Uses pandas and the scikit-surprise package to process large-scale datasets and train models efficiently.

---

### [rossmann-store-sales-prediction.ipynb](./rossmann-store-sales-prediction.ipynb)
**Regression, XGBoost, Neural Networks, Python, PyTorch**

Solves the Rossmann Store Sales prediction problem using XGBoost and neural network models with embedding layers in PyTorch. Covers feature engineering, encoding techniques, and cross-validation pipelines.

---

### [statistical_computation_agent.ipynb](./statistical_computation_agent.ipynb)
**Statistical Automation, Python, smolagents**

Demonstrates building a statistical computation agent capable of reading CSVs, extracting columns, computing means and correlations, using the smolagents framework in Python.

---

## Repository Structure

- All notebooks are in Jupyter format (`.ipynb`).
- Most experiments and projects use **Python 3** and popular data science libraries.
- See individual notebooks for detailed documentation, code, and results.
