# Predicting Credit Defaults

## Overview
This project analyzes and predicts credit defaults using machine learning models. The study examines significant explanatory variables impacting credit default probabilities and validates their importance through hypothesis testing.

## Research Hypothesis

- **Null Hypothesis (\( H_0 \))**: The selected explanatory variables **do not have a significant impact** on the probability of default.
- **Alternative Hypothesis (\( H_1 \))**: The selected explanatory variables **have a significant impact** on the probability of default.

The analysis involves statistical testing and machine learning models to explore relationships and predict outcomes.

## Requirements
To run this notebook, ensure the following libraries are installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn ucimlrepo imblearn statsmodels
```

## Contents
The notebook includes:

1. **Data Loading and Exploration**:
   - Imports and prepares the dataset.
   - Visualizes and summarizes data distributions.

2. **Feature Engineering**:
   - Processes data for model compatibility.
   - Handles imbalanced datasets using techniques like SMOTE.

3. **Model Building and Evaluation**:
   - Trains machine learning models such as Logistic Regression, Decision Trees, and Random Forests.
   - Evaluates models with performance metrics like accuracy, precision, recall, and AUC.

4. **Statistical Analysis**:
   - Tests the significance of predictors.
   - Validates the null hypothesis.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Credit_prediction.ipynb
   ```

3. Execute cells in order.

## Results
The results include:
- Statistical evidence supporting significant predictors of credit default.
- Model comparisons for predictive accuracy and reliability.

## Libraries Used
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-Learn**
- **Statsmodels**
- **Imbalanced-learn**
