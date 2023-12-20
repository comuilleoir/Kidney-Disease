# Chronic Kidney Disease Prediction Analysis

## Project Overview
This project applies machine learning techniques to predict Chronic Kidney Disease (CKD). Utilizing a dataset with various medical measurements, it explores the challenges in handling high-dimensional data and examines the effectiveness of logistic regression and other models. The project also assesses the potential of synthetic data to increase sample size and improve predictive accuracy.

## Methodology
- **Data Sources:** Utilized a dataset containing key medical measurements relevant to CKD.
- **Data Preprocessing:** Employed `StandardScaler` and `LabelEncoder` for preprocessing data, essential for accurate model training.
- **Synthetic Data Generation:** Used synthetic data generation techniques to expand the dataset, aiding in robust model training.
- **Machine Learning Models:** Began with Logistic Regression, then explored alternative models due to high dimensionality challenges. Additional models include Random Forest and Neural Networks.
- **Evaluation Metrics:** Applied accuracy score, confusion matrix, ROC curve, and other metrics for comprehensive model evaluation.
- **Technologies Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn.

## Key Findings
- Identified limitations of logistic regression in the context of high-dimensional data.
- Evaluated the impact of synthetic data on model accuracy.
- Assessed and compared the predictive performance of various machine learning models on CKD diagnosis.

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

## Conclusion
This project underscores the intricacies of using machine learning for medical diagnosis, especially in CKD. It highlights the importance of selecting appropriate models and techniques in the context of high-dimensional data and provides valuable insights for future research in medical data analytics.

