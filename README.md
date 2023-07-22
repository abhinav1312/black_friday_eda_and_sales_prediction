# Black Friday Sale EDA and Purchase Prediction

This repository contains a Python notebook for performing Exploratory Data Analysis (EDA) on a Black Friday sales dataset and building a purchase prediction model based on customer demographics and purchase behavior. The dataset used in this analysis contains information about customer demographics, purchase details, and product categories during a Black Friday sale.

## Dataset Description
The dataset contains the following features:
- User_ID: Unique identifier for each customer
- Gender: Gender of the customer (Male or Female)
- Age: Age group of the customer
- Occupation: Occupation code of the customer
- City_Category: Category of the city where the customer resides (A, B, or C)
- Stay_In_Current_City_Years: Number of years the customer has been living in the current city
- Marital_Status: Marital status of the customer (1 for married, 0 for unmarried)
- Product_ID: Unique identifier for each product
- Product_Category_1, Product_Category_2, Product_Category_3: Category codes of the products purchased
- Purchase: Purchase amount in dollars

## Table of Contents
1. Introduction
   - Overview of the Black Friday sales dataset
   - Dataset source and description
   
2. Exploratory Data Analysis (EDA)
   - Data loading and initial exploration
   - Data cleaning and handling missing values
   - Data visualization:
     - Customer demographics analysis
     - Product category insights
     - Purchase behavior analysis
     - Correlation between variables
   
3. Purchase Prediction Model
   - Data preprocessing:
     - Feature selection and engineering
     - One-Hot Encoding categorical variables
     - Train-test split
   - Model selection:
     - Comparison of different models (e.g., XGBoost, Random Forest, etc.)
     - Hyperparameter tuning using GridSearchCV
   - Model evaluation:
     - Evaluation metrics (e.g., mean squared error, R-squared)
     - Confusion matrix and classification report
   
4. Conclusion
   - Summary of key insights from EDA
   - Evaluation of the purchase prediction model
   - Potential areas of improvement
   
5. Usage
   - Step-by-step guide to execute the Python notebook
   
6. Dependencies
   - Required Python libraries and their versions
   
7. Data Source
   - Link to the dataset used in the analysis
   
8. Acknowledgments
   - Credit to the data source or any references used in the notebook
   
9. License
   - License information for the notebook
   
10. Contact
    - Contact details for the author or contributors of the notebook

## Note
- The notebook includes detailed explanations and code comments for each step.
- Visualizations will be created using popular Python libraries such as matplotlib and seaborn.
- The purchase prediction model will be built using scikit-learn.
- This notebook is meant for educational and analytical purposes, and it can be customized for specific business applications or extended for more in-depth analysis.

## Usage
1. Clone the repository to your local machine.
2. Install the required Python libraries using `pip install pandas numpy matplotlib seaborn scikit-learn xgboost`.
3. Open the Jupyter Notebook and run the `black_friday_eda_and_prediction.ipynb` file.
4. Follow the step-by-step guide in the notebook to perform EDA and build the purchase prediction model.

## Data Source
The dataset used in this analysis is available from [Kaggle](https://www.kaggle.com/mehdidag/black-friday). Please refer to the link for more details on the dataset.

## Acknowledgments
- The Black Friday sales dataset used in this analysis is provided by Kaggle.
- We acknowledge the creators of the Python libraries used in this notebook for their valuable contributions to the data science community.

