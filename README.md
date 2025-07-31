# Titanic Survival Prediction – Machine Learning Project

This assignment explores machine learning techniques to predict passenger survival using the Titanic dataset. The project involves end-to-end steps including data cleaning, feature engineering, model training, and evaluation.

## Dataset

The dataset used is the classic Titanic dataset from Kaggle:
- [train.csv](https://www.kaggle.com/c/titanic/data)

Each row represents a passenger and includes features like class, sex, age, family relations aboard, fare, and survival outcome.

## Objective

To build a predictive model that can classify whether a passenger survived the Titanic disaster based on known attributes.

## Features Used

- `pclass` (Passenger class)
- `sex`
- `age`
- `siblings_spouses`
- `parents_children`
- `fare`
- `embarked` (Port of embarkation)

## ⚙️ Workflow Summary

1. **Data Loading**
   - Read `train.csv` from Google Drive.
   - Rename columns for clarity.

2. **Data Cleaning**
   - Handle missing values in `age`, `fare`, and `embarked`.
   - Drop uninformative columns like `cabin`, `name`, and `ticket`.

3. **Feature Engineering**
   - Encode categorical features (`sex`, `embarked`).
   - Normalize or scale numerical features if needed.

4. **Modeling**
   - Train models including:
     - Logistic Regression
     - Decision Tree
     - Random Forest
   - Use accuracy as the primary evaluation metric.

5. **Model Evaluation**
   - Evaluate model performance on validation data.
   - Compare performance across different algorithms.

6. **Prediction**
   - Predict survival status on new/unseen data if applicable.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

## Skills Demonstrated

- Data preprocessing and cleaning
- Feature selection and encoding
- Model training and comparison
- Evaluation using accuracy and other metrics

## How to Use

1. Open the notebook `Titanic.ipynb` in Google Colab.
2. Mount Google Drive and ensure `train.csv` is in the correct path.
3. Run all cells in sequence to preprocess data and train models.
4. Experiment with different models and hyperparameters to improve performance.

## Author

Raghda Haikal  


---

