# Machine Learning–Based Breast Cancer Prediction

## Overview
This project applies supervised machine learning techniques to classify breast cancer tumors as **benign** or **malignant**, using diagnostic features derived from fine needle aspirate (FNA) images of breast tissue.

This work was completed as part of a **Master of Data Science** thesis at Charles Darwin University.

---

## Problem Statement
Early detection of breast cancer significantly improves patient outcomes, yet manual diagnosis can be time-consuming and costly. This project explores whether machine learning classifiers can reliably predict cancer presence using structured diagnostic data.

---

## Dataset
- Source: Wisconsin Breast Cancer Diagnostic Dataset
- Samples: 569 observations
  - 357 benign
  - 212 malignant
- Features: 30 real-valued attributes describing cell nucleus characteristics
- Missing Values: None

---

## Methodology
1. Data preprocessing
   - Label encoding
   - Feature normalization
   - Train–test split (80/20)
2. Model training
   - Random Forest
   - Support Vector Machine (SVM)
   - Gradient Boosting Machine (GBM)
   - K-Nearest Neighbours (KNN)
   - Naïve Bayes
3. Model evaluation
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC-AUC

---

## Results

| Model | Accuracy |
|------|----------|
| Naïve Bayes | **97.36%** |
| Random Forest | 96.49% |
| SVM | 96.00% |
| GBM | 95.61% |
| KNN | 95.61% |

---

## Key Insights
- Naïve Bayes achieved the highest accuracy on this dataset.
- Simple probabilistic models can outperform more complex classifiers on well-structured medical data.
- All models achieved over 95% accuracy, indicating strong predictive signal.

---

## Limitations and Future Work
- Performance may degrade on larger or more complex datasets.
- Feature independence assumptions limit Naïve Bayes scalability.
- Future improvements include:
  - Deep learning models
  - Larger and more diverse datasets
  - Ensemble methods

---

## Repository Structure
- `data/` – Raw and processed datasets
- `notebooks/` – Jupyter notebooks with analysis and modeling
- `reports/` – Final thesis report (PDF)

---

## Skills Demonstrated
- Data preprocessing and feature engineering
- Supervised machine learning
- Model evaluation and comparison
- Python (pandas, scikit-learn)

---

## Author
**Sameen Sadman**  
Master of Data Science, Charles Darwin University  
Graduated: July 2024
