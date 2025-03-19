### Social-Network-Ads-Analysis-and-Prediction

## Project Overview
This repository contains a machine learning analysis of the "Social_Network_Ads.csv" dataset, focusing on predicting purchase behavior based on demographic features. The project employs classification algorithms to identify key patterns in customer response to advertising.

# Feature Engineering
The analysis focuses on the relationship between demographic attributes (Age and EstimatedSalary) and purchase decisions. Feature engineering considerations include:

Feature scaling to normalize Age and EstimatedSalary distributions

Potential one-hot encoding of Gender category

Investigation of interaction effects between Age and Salary

# Model Implementation
The project implements several classification algorithms to predict purchase behavior:

Decision Tree and Random Forest

Feature importance analysis

Tree depth optimization and pruning strategies

# Model Evaluation Metrics
Performance evaluation employs the following metrics:

Classification accuracy

Precision and recall scores

F1-score for balanced evaluation

ROC-AUC analysis for model comparison

Cross-validation to ensure generalizability

# Key Findings
Statistical analysis of the dataset reveals:

Age-Purchase Relationship

Purchase likelihood increases significantly after age 40

The age range 45-55 shows the highest conversion rate

Salary-Purchase Correlation

Strong positive correlation between salary level and purchase probability

Purchase likelihood increases substantially above the median salary ($70,000)

# Feature Importance

EstimatedSalary emerges as the strongest predictor

Age provides complementary predictive power

Combined Age-Salary interaction creates clearly separable decision regions

Model Performance Comparison

Non-linear models outperform linear classifiers

SVM with RBF kernel achieves optimal balance of precision and recall

Random Forest provides robust performance with interpretable feature importance

Decision Boundary Analysis
The analysis includes visualization of decision boundaries that demonstrates:

Clear separation between purchase/non-purchase regions in the Age-Salary feature space

Non-linear relationship between variables and purchase decisions

High-confidence prediction regions for targeted marketing


# Visualization of decision boundaries and model comparison
Technical Insights
The classification problem exhibits moderate complexity with potential for high predictive accuracy

Feature scaling proves essential due to the different scales of Age and EstimatedSalary

The 35.75% positive class rate suggests slight class imbalance requiring appropriate handling

The dataset's statistical properties (as shown in the descriptive statistics) indicate well-distributed features suitable for ML modeling

# Conclusions and Applications
The machine learning analysis provides actionable insights for targeted advertising:

Precise identification of high-value customer segments based on demographic profiles

Probability-based targeting to maximize advertising ROI

Feature importance analysis to guide data collection priorities

Decision boundary visualization for intuitive business strategy development

# Requirements
Python 3.8+
pandas
numpy
matplotlib
seaborn

scikit-learn

Usage
Execute the Jupyter notebook to reproduce the analysis:

text
jupyter notebook newtork_ad.ipynb
