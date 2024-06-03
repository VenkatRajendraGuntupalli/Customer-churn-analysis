### README.md

# Customer Churn Analysis

## Overview

This project aims to analyze and predict customer churn for a telecommunications company using machine learning techniques. Customer churn occurs when customers stop doing business with a company. By predicting which customers are likely to churn, companies can take proactive measures to retain them.

## Dataset

The dataset used for this project is the "Telco Customer Churn" dataset, which is publicly available. It contains information about customer demographics, account information, and service usage.

- **File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Source:** [Kaggle Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

## Project Steps

### 1. Data Exploration and Preprocessing

- **Data Loading:** Load the dataset using pandas.
- **Data Inspection:** Inspect the dataset to understand its structure and summary statistics.
- **Data Cleaning:** Handle missing values, convert data types, and remove unnecessary columns.
- **Feature Encoding:** Convert categorical variables into numerical values using encoding techniques.

### 2. Data Visualization

- **Target Variable Distribution:** Visualize the distribution of the target variable 'Churn'.
- **Boxplot Analysis:** Analyze the relationship between 'Churn' and 'Monthly Charges'.

### 3. Data Splitting

- **Feature and Target Separation:** Separate the dataset into features (X) and target variable (y).
- **Train-Test Split:** Split the dataset into training and testing sets.

### 4. Model Training and Evaluation

#### Model 1: Logistic Regression

- **Training:** Train a logistic regression model on the training data.
- **Evaluation:** Evaluate the model's accuracy and confusion matrix on the test data.

#### Model 2: K-Nearest Neighbors (KNN)

- **Training:** Train a KNN model on the training data.
- **Evaluation:** Evaluate the model's accuracy and confusion matrix on the test data.

### 5. Results

- **Logistic Regression:** Achieved an accuracy of 78.39%.
- **K-Nearest Neighbors:** Achieved an accuracy of 77.26%.

The logistic regression model outperformed the KNN model in predicting customer churn.

### 6. Conclusion

Using the logistic regression model, companies can predict customer churn with an accuracy of 78.39%. This allows them to take proactive measures to retain customers, such as offering promotions and discounts.

## Getting Started

### Prerequisites

- Python 3.x
- Google Colab (or Jupyter Notebook)
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

### Installation

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Running the Project

1. Clone the repository:

```bash
git clone https://github.com/yourusername/customer-churn-analysis.git
cd customer-churn-analysis
```

2. Open the Jupyter Notebook or Google Colab and run the cells in the provided order to reproduce the analysis and results.

## Files in the Repository

- `Customer_Churn_Analysis.ipynb`: The Jupyter Notebook containing the complete analysis and code.
- `WA_Fn-UseC_-Telco-Customer-Churn.csv`: The dataset file used for the analysis.

## Authors

- Venkat Rajendra Guntupalli

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Kaggle Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn) for providing the dataset.

---
