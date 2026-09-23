# DataVine Analytics — Summative Lab

## Project Overview

This project applies machine learning techniques to three practical
business problems for DataVine Analytics.

The analysis follows a complete data science workflow, including:

- Data preparation and quality checks
- Feature standardization
- Principal Component Analysis (PCA)
- Hyperparameter tuning
- Classification
- Recommendation systems
- K-Means clustering
- Gaussian Mixture Models (GMM)
- Model evaluation and interpretation
- Data visualization

---

## Business Problems

### 1. Wine Classification

A premium wine distributor needs to classify wines based on their
chemical properties.

**Method used:**
- StandardScaler
- PCA
- k-Nearest Neighbors (k-NN)
- GridSearchCV

**Key results:**
- Original features: 13
- PCA components: 10
- Variance retained: 96.24%
- Best number of neighbors: 18
- Best distance metric: Euclidean
- Cross-validation accuracy: 97.91%
- Test accuracy: 100%

---

### 2. Agricultural Feed Recommendation

An agricultural supply company wants to recommend similar feed types
based on chicken weight performance.

The Chickwts dataset was used as a proxy for feed performance.

**Method used:**
- Data cleaning
- Feed-level aggregation
- StandardScaler
- PCA
- Cosine similarity

**Feed types analyzed:**
- Horsebean
- Linseed
- Soybean
- Sunflower
- Meatmeal
- Casein

The recommendation analysis compares feed types based on their average
chicken weight.

---

### 3. Regional Crime Pattern Analysis

A public policy research firm wants to identify patterns in crime
statistics across US states.

**Features selected:**
- Murder
- Assault
- Rape

**Methods used:**
- StandardScaler
- PCA
- K-Means clustering
- Elbow method
- Gaussian Mixture Model (GMM)
- Bayesian Information Criterion (BIC)

**Key results:**
- K-Means: 4 clusters selected using the elbow method
- GMM: 2 components selected using BIC

---

## Technologies and Libraries

The project was developed using Python and Jupyter Notebook.

### Libraries

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## Repository Structure

```text
DataVine_Analytics_Summative_Lab/
│
├── DataVine_Analytics_Summative_Lab.ipynb
├── wine.csv
├── chickwts.csv
├── USArrests.csv
└── README.md