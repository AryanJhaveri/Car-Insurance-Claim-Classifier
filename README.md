# Car Insurance Claim Prediction

## About the Project
This project focuses on predicting the likelihood of car insurance claims within the next six months, leveraging a Kaggle dataset with a diverse range of policyholder features. 

### Repository Contents
- [dataset](car_insurance_dataset.csv)
- [Jupyter Notebook](car_insurance_claim_classifier.ipynb)
  
## Feature Selection
I employed SelectKBest with the f_classif function, a technique that highlights the statistical significance of features for our predictive model, ensuring only the most relevant variables are used.

## Exploratory Data Analysis (EDA)
The EDA phase included a variety of visualization techniques, from histograms to heatmaps, which were instrumental in identifying data trends and distributions, as well as a significant class imbalance.

## Data Preparation
1. **Balancing the Data:** To tackle the class imbalance, I implemented SMOTE and RandomUnderSampler, techniques that are crucial for improving model performance in imbalanced datasets.
2. **Preparing Data for ML Models:** The categorical data underwent one-hot encoding, a vital step for model compatibility with non-numeric data.

## Machine Learning Models
The project employed Logistic Regression, Random Forest, SVM, and XGBoost. Each model was meticulously evaluated on metrics including sensitivity, specificity, and AUC-ROC, providing a holistic view of their performance.

## Results
Assessing the models under different data conditions (original, oversampled, and undersampled) allowed for a nuanced understanding of each model's capabilities in varied scenarios.

## Conclusion
The XGBoost model, particularly on the undersampled dataset, achieved the highest sensitivity, a critical metric for the insurance domain.
