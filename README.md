# Email-Campaign-Effectiveness-Prediction
I created a machine learning model to characterize email behaviour in Gmail-based email marketing campaigns. Through data analysis, feature engineering, model selection, training, evaluation, and optimization. Also, I developed a robust model that provides valuable insights for business decision-making. 

This repository contains the implementation and evaluation of various machine learning models using different data resampling techniques. The models include Decision Trees, Random Forests, and CatBoost Classifiers. The resampling techniques used are SMOTE, SMOTETomek, and Random Undersampling. The performance of each model is compared and visualized using different charts.

# **Table of Contents**

Project Overview

Datasets

Visualizations

Hypothesis Testing

Resampling Techniques

Models Implemented

Results

Conclusion

# **Project Overview**

This project compares the performance of different machine learning models trained on various resampled datasets. The models are evaluated based on their accuracy, precision, recall, and F1 score. The goal is to understand how resampling techniques affect the performance of each model.

# **Datasets**
The dataset used in this project is a hypothetical dataset for classification tasks. The dataset is divided into training and testing sets.

# **Visualizations**
The performance metrics are visualized using various types of charts to provide a clear comparison between the models. Below are examples of the visualizations used:

**Line Chart**
This chart compares the accuracy, precision, recall, and F1 score of the Random Forest models trained with different resampling techniques.

**Scatter Plot**
A scatter plot visualizing the performance of the CatBoost models across different metrics.

**Heatmap**
A heatmap representing the confusion matrix of the optimized Decision Tree model trained on SMOTETomek resampled data.

# **Statistical Tests**

**Hypothetical Statement - 1**
**Test Used:** Paired t-test

**Reason:** The paired t-test is suitable for comparing the performance metrics of the same model on different resampled datasets to determine if there are statistically significant differences.

**Hypothetical Statement - 2**
**Test Used:** Independent t-test

**Reason:** The independent t-test is chosen to compare the performance metrics of different models trained on the same dataset to see if their performance differs significantly.

**Hypothetical Statement - 3**
**Test Used:** ANOVA (Analysis of Variance)

**Reason:** ANOVA is used to compare the means of multiple groups (more than two) to evaluate the performance metrics across different models trained with various data resampling techniques.

# **Resampling Techniques**
The following resampling techniques are used to handle class imbalances in the dataset:

**SMOTE (Synthetic Minority Over-sampling Technique)**
**SMOTETomek (Combination of SMOTE and Tomek Links)**
**Random Undersampling**
**Models Implemented**
**Decision Tree Classifier**
**Random Forest Classifier**
**CatBoost Classifier**
**Evaluation Metrics**

# **The models are evaluated using the following metrics:**

**Accuracy**

**Precision**

**Recall**

**F1 Score**

**Results**

The performance of each model on different resampled datasets is stored in a dictionary called final_dict. This dictionary contains the evaluation metrics for each model and resampling technique combination.

# **Conclusion**
This project demonstrates the impact of different resampling techniques on the performance of various machine learning models. By comparing evaluation metrics and visualizing the results, it provides insights into the effectiveness of each technique and model combination.
