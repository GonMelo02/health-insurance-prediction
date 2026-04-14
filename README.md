# Health Insurance Prediction

Binary classification project predicting health insurance ownership 
from demographic and socioeconomic data (US customers dataset).

## Results

| Model | F1 Score (Test) |
|-------|----------------|
| Gradient Boosting | **0.733** |
| SVM | 0.729 |
| Logistic Regression | 0.713 |
| Gaussian Naive Bayes | 0.682 |
| KNN | 0.665 |

Best model: Gradient Boosting (F1 = 0.733), selected for best 
generalization on unseen data.

## Methods
- EDA + feature engineering on demographic/socioeconomic features
- Preprocessing optimization (scaling, encoding, imbalance handling)
- Cross-validated comparison of 5 classifiers
- Model selection based on F1-score (precision/recall balance)

## Context
Developed for a Kaggle-based competition (MSc Bioinformatics, FCUP). 
Models evaluated on a masked test set via Kaggle leaderboard, 
scored by F1.

## Stack
Python · scikit-learn · pandas · matplotlib · seaborn

## Run locally
pip install -r requirements.txt
jupyter notebook notebook.ipynb
