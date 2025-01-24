# Heart-Disease-Prediction


### Predicting Heart Disease with Machine Learning

This project leverages machine learning to predict the risk of heart disease using the Heart Failure Prediction Dataset from Kaggle. Our team explored several models and identified the Random Forest algorithm as the best-performing model, achieving an AUC-ROC score of 0.947.

### Dataset

The dataset contains 918 records with 11 attributes that are significant predictors of heart disease, including demographic, clinical, and symptomatic data. The target variable indicates the presence of heart disease (1) or normal status (0).

### Methods

1. Data Preprocessing
	•	Handling Missing Values: The dataset contained no missing values.
	•	Feature Scaling: Robust scaling was applied to continuous variables to minimize the effect of outliers.
	•	Categorical Encoding: Categorical variables were encoded using one-hot encoding to ensure compatibility with non-tree-based algorithms.

2. Visualization
	•	Histograms and scatter plots were used to explore variable distributions and relationships.
	•	Correlation heatmaps identified multicollinearity and key predictors.

3. Modeling

The following models were implemented and evaluated:
	•	Logistic Regression (baseline)
	•	Random Forest
	•	XGBoost
	•	Gradient Boosting
	•	Support Vector Machine (SVM)

Key Results:
	•	Random Forest: Best AUC-ROC (0.947) and balanced feature importance.
	•	SVM: Highest accuracy (91%) and precision (92%), ideal for high-risk patient identification.

4. Feature Importance
	•	ST_Slope_Up was consistently identified as the most critical predictor across Random Forest and XGBoost models.
	•	Other key features included MaxHR (Maximum Heart Rate) and ST_Slope_Flat.

5. Optimization
	•	Hyperparameters of the Random Forest model were fine-tuned, slightly improving the AUC-ROC to 0.948.

### Results

The Random Forest model emerged as the best option due to its interpretability and balanced use of predictors, making it ideal for clinical applications.

### Conclusion and Future Work

This study demonstrates the potential of machine learning for early detection of heart disease. Future research should focus on:
	•	Adding lifestyle and genetic factors to enhance prediction accuracy.
	•	Testing models across diverse datasets to improve generalizability.

Files

1.	HeartDisease.ipynb: Jupyter Notebook containing the code for data preprocessing, visualization, modeling, and evaluation.
2.	Report.pdf: Detailed report describing the methodology, results, and insights.


  Dataset: [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data "Heart Failure Prediction Dataset")
 

