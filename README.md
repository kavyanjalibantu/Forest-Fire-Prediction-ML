# Forest Fire Prediction using Machine Learning

## Overview

This project focuses on predicting forest fire occurrences using Machine Learning techniques. The Algerian Forest Fire Dataset is used to build and evaluate classification models that can identify whether a fire is likely to occur based on environmental and weather-related factors.

The project includes data preprocessing, feature engineering, model training, hyperparameter tuning, performance evaluation, and comparison of multiple machine learning algorithms.


## Dataset

The project uses the **Algerian Forest Fire Dataset**, which contains meteorological and fire weather index attributes collected from regions in Algeria.

### Features

* Temperature
* Relative Humidity (RH)
* Wind Speed (Ws)
* Rainfall
* Fine Fuel Moisture Code (FFMC)
* Duff Moisture Code (DMC)
* Drought Code (DC)
* Initial Spread Index (ISI)
* Buildup Index (BUI)
* Fire Weather Index (FWI)

### Target Variable

* **Fire (1)**
* **Not Fire (0)**


## Technologies and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost


## Machine Learning Models

The following classification models were implemented and compared:

### 1. XGBoost Classifier

* Gradient boosting-based ensemble model
* Hyperparameter tuning using GridSearchCV

### 2. Random Forest Classifier

* Ensemble learning technique using multiple decision trees
* Optimized using GridSearchCV

### 3. Support Vector Machine (SVM)

* Kernel-based classification algorithm
* Standardized features using StandardScaler
* Hyperparameter tuning using GridSearchCV



## Methodology

1. Data Cleaning and Preprocessing
2. Feature Selection
3. Train-Test Split
4. Hyperparameter Optimization using GridSearchCV
5. Model Training
6. Performance Evaluation
7. Model Comparison
8. Feature Importance Analysis


## Evaluation Metrics

The models were evaluated using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* ROC-AUC Score
* Confusion Matrix
* Classification Report
* ROC Curve Analysis

Additionally, **10-Fold Cross Validation** was performed to ensure model robustness and reliability.


## Visualizations

The project includes:

* Confusion Matrix Heatmaps
* ROC Curve Comparison
* Feature Importance Plots
* Performance Comparison of Models


## Project Structure

```text
Forest-Fire-Prediction-ML/
│
├── Algerian_Forest_Data1.csv
├── Algerian_Forest_data.ipynb
├── XGB_RF_SVM_Final.py
├── README.md
│
└── model_comparison_results.csv
```

## How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/Forest-Fire-Prediction-ML.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

### Run the Project

```bash
python XGB_RF_SVM_Final.py
```

Or open and run:

```text
Algerian_Forest_data.ipynb
```

using Jupyter Notebook or Google Colab.



## Results

The project compares the performance of XGBoost, Random Forest, and Support Vector Machine models for forest fire classification and identifies the most effective model based on evaluation metrics and ROC-AUC performance.



## Author

**Bantu Kavyanjali**

Machine Learning Project – Forest Fire Prediction and Classification
