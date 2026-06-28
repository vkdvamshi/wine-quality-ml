# 🍷 Wine Quality Classification

Predicting wine quality from physicochemical properties (acidity, sugar, pH, alcohol, sulphates, …) using the [Kaggle WineQT dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset).

## Overview
`wine-quality.ipynb` walks through a complete supervised-learning workflow:

- **EDA** — feature distributions, correlation heatmap, quality-class balance
- **Preprocessing** — scaling, train/test split, handling class imbalance
- **Modeling** — classification algorithms compared (Logistic Regression, Random Forest, SVM, gradient boosting)
- **Evaluation** — accuracy, precision/recall, confusion matrix, feature importance

## Data
The dataset (`data/WineQT.csv`) is included — it's a small, public physicochemical wine dataset.

## Run it
```bash
pip install -r requirements.txt
jupyter notebook wine-quality.ipynb
```

## Author
**Vamshi Krishna Damidi** — Data & AI Engineer
🌐 [Portfolio](https://vkdvamshi.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/vamshi-krishna-damidi-b6434512/) · 🐙 [GitHub](https://github.com/vkdvamshi)
