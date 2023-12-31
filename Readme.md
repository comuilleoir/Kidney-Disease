# Chronic Kidney Disease Prediction Analysis

## Project Overview
This project applies machine learning techniques to predict Chronic Kidney Disease (CKD). Utilizing a dataset with various medical measurements, it explores the challenges in handling high-dimensional data and examines the effectiveness of logistic regression and other models. The project also assesses the potential of synthetic data to increase sample size and improve predictive accuracy.

## Methodology
- **Data Sources:** Utilized a dataset containing key medical measurements relevant to CKD.
- **Data Preprocessing:** Employed `StandardScaler` and `LabelEncoder` for preprocessing data, essential for accurate model training.
- **Synthetic Data Generation:** Used synthetic data generation techniques to expand the dataset, aiding in robust model training.
- **Machine Learning Models:** Began with Logistic Regression, then explored alternative models due to high dimensionality challenges. Additional models include Random Forest and Neural Networks.
- **Evaluation Metrics:** Applied accuracy score, confusion matrix, ROC curve, and other metrics for comprehensive model evaluation.

## Key Findings
- Identified limitations of logistic regression in the context of high-dimensional data.
- Evaluated the impact of synthetic data on model accuracy.
- Assessed and compared the predictive performance of various machine learning models on CKD diagnosis.

## Technologies Used
- **Python**: For scripting, data preprocessing, and model implementation.
- **Machine Learning Libraries**: Utilized Python libraries like scikit-learn for model development and evaluation.

## Repository Contents
- `Data`: Includes both original and synthetic datasets.
- `Scripts`: Contains Python scripts for logistic regression analysis, data preprocessing, model training, and performance evaluation.
- `Project_Images`: Features charts and plots such as ROC curves and confusion matrices, providing insights from the analysis.

## Images and Visualizations

Optimised Logistic Regression Confusion Matrix

![Optimised Logistic Regression Confusion Matrix](https://github.com/comuilleoir/Kidney-Disease/blob/main/Project_Images/log_reg_roc.png)

Optimised Random Forest Confusion Matrix

![Optimised Random Forest Confusion Matrix](https://github.com/comuilleoir/Kidney-Disease/blob/main/Project_Images/RF_roc.png)

Optimised Neural Network Confusion Matrix

![Optimised Random Forest Confusion Matrix](https://github.com/comuilleoir/Kidney-Disease/blob/main/Project_Images/NN_roc.png)

Optimised Neural Network Loss Curve

![Optimised Random Forest Confusion Matrix](https://github.com/comuilleoir/Kidney-Disease/blob/main/Project_Images/NN_loss_1.png)

## Future Work
- **Model Optimization:** Focus on enhancing model accuracy and exploring additional machine learning algorithms.
- **Data Expansion:** Consider incorporating more diverse datasets to further validate model performance.