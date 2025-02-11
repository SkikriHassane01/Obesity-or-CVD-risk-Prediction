# Obesity Risk Prediction - Kaggle Competition

## Overview
This project is part of a Kaggle competition aimed at predicting obesity risk based on various health and lifestyle factors. The dataset contains information related to individuals' physical characteristics, habits, and health conditions.

The link of the kaggle notebook: [Obesity Risk Prediction](https://www.kaggle.com/code/hassaneskikri/obesity-risk-season-4-episode?scriptVersionId=161681157)

[UCI obecity dataset exploration and modeling](https://www.kaggle.com/code/hassaneskikri/the-uci-obesity-dataset-exploration)
## Dataset
The project utilizes the following datasets:
- `train.csv`: Training dataset provided by the Kaggle competition.
- `test.csv`: Test dataset for making predictions.
- `ObesityDataSet.csv`: An additional dataset with obesity-related information.

## Approach
The workflow includes:
1. **Data Preprocessing:**
   - Handling missing values using `SimpleImputer`.
   - Feature engineering and transformations.
   
2. **Exploratory Data Analysis (EDA):**
   - Visualizing distributions and correlations using `seaborn` and `matplotlib`.

3. **Modeling:**
   - Training models using `XGBoostClassifier`.
   - Hyperparameter tuning with `Optuna`.
   - Cross-validation for model evaluation.

4. **Predictions & Submission:**
   - Generating predictions on the test dataset.
   - Preparing submission files for Kaggle.
5. **Final Accuracy:**
![image](https://github.com/user-attachments/assets/abd37031-a3aa-4f2e-ae8f-dd7cf7dd625d)

## Dependencies
The project requires the following libraries:
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `xgboost`, `optuna`
- `tqdm` for progress tracking

## Usage
To run the notebook:
```bash
pip install -r requirements.txt  # Install dependencies
```
and execute the Jupyter Notebook to explore the analysis step by step.

## Competition
This project is part of the Kaggle **Playground Series - Season 4, Episode 2** competition. The goal is to create the best-performing model for obesity risk prediction.
