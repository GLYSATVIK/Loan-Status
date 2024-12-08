
# Loan Status Prediction

This project leverages machine learning techniques to predict the approval status of loans based on various features, such as applicant details and loan attributes. It provides insights into the patterns and factors influencing loan approvals, enabling better decision-making for financial institutions.

## Table of Contents
1. [Overview](#overview)  
2. [Dataset](#dataset)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Modeling Approach](#modeling-approach)  
6. [Results](#results)  
7. [Future Work](#future-work)  
8. [Contributing](#contributing)  
9. [License](#license)  

## Overview
The goal of this project is to build a robust model to classify loans into approved or not-approved categories. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning modeling.

## Dataset
The dataset used for this project contains attributes related to applicants and their loans, such as:
- **Applicant Income**
- **Credit History**
- **Loan Amount**
- **Loan Term**
- **Dependents**
- **Marital Status**
- **Education**

The data is cleaned and prepared to handle missing values and outliers effectively.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/GLYSATVIK/Loan-Status.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the notebook to explore the dataset, preprocess data, and train models:
1. Open the Jupyter notebook:
   ```bash
   jupyter notebook Loan Status Prediction.ipynb
   ```
2. Follow the steps to execute each cell for data exploration, preprocessing, modeling, and evaluation.

## Modeling Approach
- Models used include:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - Gradient Boosting
- Evaluation metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score

Hyperparameter tuning is performed to optimize model performance.

## Results
The best-performing model achieves:
- Accuracy on Training Data: 79.86%
- Accuracy on Test Data: 83.33%  

## Future Work
- Incorporate additional features to improve model performance.
- Explore advanced techniques like ensemble learning and deep learning.
- Deploy the model using Flask or FastAPI for real-world applications.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or feature additions.

## License
This project is licensed under the MIT License.

