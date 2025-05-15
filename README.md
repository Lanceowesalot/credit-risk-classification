![HQ graphic](https://github.com/Lanceowesalot/Mars-News/blob/main/Images/Mars%20Image.png)

# Credit Risk Analysis

This project evaluates credit risk using predictive modeling techniques. It uses clustering and classification methods to assess the likelihood of credit default, based on historical financial data.

---

##  Table of Contents
- [Project Overview](#project-overview)
- [How to Load and Use the Code](#how-to-load-and-use-the-code)
- [Summary of Code](#summary-of-code)
- [Interprtation](#interpretation)
- [Conclusion and Analysis](#conclusion-and-analysis)
- [Dependencies](#dependencies)

---

##  Project Overview

This notebook guides the user through a supervised machine learning workflow for evaluating credit risk. Using the `lending_data.csv` dataset, the model learns to predict whether a loan is high-risk or low-risk based on a variety of financial features.

The main objectives are:
- Load and preprocess labeled credit data.
- Train a logistic regression model on the data.
- Evaluate model performance using confusion matrices and classification reports.
- Discuss the efficacy and reliability of the model.

---

##  How to Load and Use the Code

1. **Environment Setup**: Ensure the following Python packages are installed:
   ```bash
   pip install pandas scikit-learn numpy
   ```

2. **Run the Notebook**:
   - Launch Jupyter Notebook.
   - Open `credit_risk_classification.ipynb`.
   - Execute all cells in order.

3. **Input Data**:
   - Ensure `Resources/lending_data.csv` is in the correct folder relative to the notebook.

---

##  Summary of Code

- **Data Loading**:
  - Imports the dataset with Pandas.
  - Previews the structure of loan-related features.

- **Preprocessing**:
  - Splits the dataset into feature matrix `X` and target vector `y`.
  - Applies a train/test split.

- **Model Training**:
  - Trains a logistic regression classifier on the training data.

- **Evaluation**:
  - Outputs a confusion matrix and classification report to assess accuracy, precision, and recall.

---

###  Interpretation

The clustering reveals patterns in borrower profiles:
- One cluster may represent high-risk individuals (e.g., low income, high debt-to-income ratio).
- Another cluster may consist of low-risk borrowers with strong financial profiles.
- Visualization helps identify the spread and overlap of credit behaviors.

These insights are useful for:
- Lending decisions
- Risk mitigation strategies
- Understanding creditworthiness patterns

---

##  Conclusion and Analysis

The logistic regression model demonstrates basic classification performance, suitable for a baseline model. However:

- Precision and recall should be closely monitored due to the potential real-world risks of misclassifying loan statuses.
- Future iterations could explore more robust classifiers (e.g., Random Forests, Gradient Boosting) and feature scaling or engineering to enhance performance.
- Model interpretability and fairness are important next steps if this were to be used in a real-world setting.
---

##  Dependencies

- Python 3.7+
- pandas
- scikit-learn



---


