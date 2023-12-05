# Water Potability Prediction Project

## Objective:
The project aims to predict water potability based on water quality attributes using machine learning techniques.

## Steps Taken:
1. **Data Loading and Exploration:**
   - Loaded the dataset from [Water Quality and Potability on Kaggle](https://www.kaggle.com/datasets/uom190346a/water-quality-and-potability) and explored its features.
   - Checked for missing values and explored the distribution of the target variable.

2. **Data Preprocessing:**
   - Handled missing values through imputation.
   - Checked for outliers and decided to ignore them for the initial analysis.
   - Split the data into training and testing sets.
   - Scaled numerical features.

3. **Modeling:**
   - Trained individual models (Random Forest and Gradient Boosting).
   - Explored feature importance for model interpretation.
   - Created an ensemble model using the VotingClassifier.

4. **Evaluation:**
   - Evaluated the models using accuracy, precision, recall, and F1-score.
   - Compared the performance of individual models and the ensemble.

## Key Findings:
- pH level and sulfate concentration are identified as the most influential features.
- The ensemble model showed improved accuracy and precision for predicting potable water.

## Next Steps:
- Hyperparameter tuning for individual models.
- Explore feature engineering techniques.
- Experiment with different ensemble strategies.
- Revisit class imbalance handling techniques.

## Dataset Source:
The dataset used in this project is sourced from [Water Quality and Potability on Kaggle](https://www.kaggle.com/datasets/uom190346a/water-quality-and-potability).

Feel free to contribute or reach out for further collaboration!

