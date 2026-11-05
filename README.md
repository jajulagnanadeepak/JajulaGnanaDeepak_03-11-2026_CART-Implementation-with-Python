# Titanic Survival Prediction using CART

## Project Overview

This project implements a **Classification and Regression Tree (CART)** machine learning algorithm to predict whether a passenger survived the Titanic disaster based on passenger information.

The project uses Python, Pandas, Seaborn, Matplotlib, and Scikit-learn to perform data preprocessing, exploratory data analysis, model training, evaluation, and prediction.

## Objectives

- Understand and explore the Titanic dataset.
- Perform data cleaning and preprocessing.
- Analyze passenger survival patterns.
- Implement a CART Decision Tree Classifier.
- Evaluate model performance.
- Predict survival for new passenger records.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Dataset

The project uses the Titanic dataset available through Seaborn.

- Original records: 891
- Target variable: `survived`
- `0` – Did Not Survive
- `1` – Survived

### Features Used

| Feature | Description |
|---|---|
| `pclass` | Passenger class |
| `sex` | Passenger gender |
| `age` | Passenger age |
| `sibsp` | Number of siblings/spouses aboard |
| `parch` | Number of parents/children aboard |
| `fare` | Ticket fare |
| `embarked` | Port of embarkation |

## Project Workflow

1. Import Libraries and Load Dataset
2. Data Understanding and Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Selection and Preprocessing
5. Train-Test Split
6. CART Model Training and Evaluation
7. New Passenger Prediction and Model Saving

## CART Model Configuration

The Decision Tree Classifier uses:

- Criterion: Gini
- Maximum Depth: 4
- Minimum Samples Split: 10
- Minimum Samples Leaf: 5
- Random State: 42

## Model Performance

| Metric | Result |
|---|---:|
| Algorithm | CART Decision Tree |
| Training Data | 80% |
| Testing Data | 20% |
| Test Accuracy | 77.65% |

The model is evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

## Project Structure

```text
Titanic-Survival-Prediction-CART/
│
├── Cart_Python_Tiitatic.ipynb
├── cart_model.pkl
├── preprocessor.pkl
├── .gitignore
└── README.md
```

## Model Saving

The trained model and preprocessing object are saved using Joblib:

- `cart_model.pkl`
- `preprocessor.pkl`

These files can be loaded later to make predictions without retraining the model.

## Key Learnings

- Data cleaning and missing-value handling.
- Exploratory data analysis.
- Categorical feature encoding.
- Decision Tree classification.
- Model evaluation and prediction.
- Saving and reusing machine learning models.

## Future Improvements

- Hyperparameter tuning.
- Compare CART with Random Forest.
- Improve survival prediction recall.
- Deploy the model using Streamlit.

## Author

**Jajula Gnana Deepak**

- GitHub: [jajulagnanadeepak](https://github.com/jajulagnanadeepak)

---
