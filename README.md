**Tobacco Use and Expenditure Analysis**

This project utilizes machine learning to explore the relationship between tobacco pricing, household income, and overall expenditure. The primary goal is to predict Tobacco Expenditure as a Percentage of Total Expenditure based on various economic indicators.

**📊 Dataset Overview**

The analysis is performed on a dataset (metrics.csv) containing 36 annual records (1980–2015) with the following key features:

Tobacco Price Index: Relative cost of tobacco over time.

Retail Prices Index: General inflation/cost of living tracker.

Real Households' Disposable Income: Adjusted income available for spending/saving.

Affordability of Tobacco Index: A measure of how accessible tobacco is relative to income.

Household Expenditure: Total and tobacco-specific spending.

🛠️ Data Preprocessing Pipeline
The notebook implements a robust preprocessing workflow to ensure data quality:

Missing Value Analysis: Identifies columns with null values (found in approximately 13.8% of the expenditure rows).

Imputation: * Numerical missing values are filled using the median to maintain central tendency without being skewed by outliers.

(Placeholder logic exists for categorical 'Sex' imputation if expanded).

Feature Scaling: Uses StandardScaler to normalize numerical features, ensuring that large-scale values (like Total Expenditure) don't overpower smaller indices.

Categorical Encoding: Includes a OneHotEncoder within a ColumnTransformer to handle potential categorical variables in future iterations.

🚀 **Technologies Used**

Python 3

Pandas: Data manipulation and structural analysis.

Scikit-Learn: Machine learning pipeline, preprocessing, and RandomForestRegressor (imported and ready for training).

NumPy: Numerical operations.

📈 **Current Progress**
[x] Initial Data Exploration (Head, Info, Describe).

[x] Data Cleaning and Imputation.

[x] Feature/Target Variable Definition.

[x] Preprocessing Pipeline Construction.

[ ] Model Training and Evaluation (Next Steps).

📝 Tobacco Use and Expenditure Analysis
This project utilizes machine learning to explore the relationship between tobacco pricing, household income, and overall expenditure. The primary goal is to predict Tobacco Expenditure as a Percentage of Total Expenditure based on various economic indicators.

📊 Dataset Overview
The analysis is performed on a dataset (metrics.csv) containing 36 annual records (1980–2015) with the following key features:

Tobacco Price Index: Relative cost of tobacco over time.

Retail Prices Index: General inflation/cost of living tracker.

Real Households' Disposable Income: Adjusted income available for spending/saving.

Affordability of Tobacco Index: A measure of how accessible tobacco is relative to income.

Household Expenditure: Total and tobacco-specific spending.

🛠️ Data Preprocessing Pipeline
The notebook implements a robust preprocessing workflow to ensure data quality:

Missing Value Analysis: Identifies columns with null values (found in approximately 13.8% of the expenditure rows).

Imputation: * Numerical missing values are filled using the median to maintain central tendency without being skewed by outliers.

(Placeholder logic exists for categorical 'Sex' imputation if expanded).

Feature Scaling: Uses StandardScaler to normalize numerical features, ensuring that large-scale values (like Total Expenditure) don't overpower smaller indices.

Categorical Encoding: Includes a OneHotEncoder within a ColumnTransformer to handle potential categorical variables in future iterations.

🚀 Technologies Used
Python 3

Pandas: Data manipulation and structural analysis.

Scikit-Learn: Machine learning pipeline, preprocessing, and RandomForestRegressor (imported and ready for training).

NumPy: Numerical operations.

📈 Current Progress
[x] Initial Data Exploration (Head, Info, Describe).

[x] Data Cleaning and Imputation.

[x] Feature/Target Variable Definition.

[x] Preprocessing Pipeline Construction.

[ ] Model Training and Evaluation (Next Steps).

📝** How to Use**
Ensure metrics.csv is in the same directory as the notebook.

Run the cells sequentially to clean the data and initialize the preprocessing pipeline.

The variable preprocessor is ready to be integrated into a Scikit-Learn Pipeline for model fitting.
Ensure metrics.csv is in the same directory as the notebook.

Run the cells sequentially to clean the data and initialize the preprocessing pipeline.

The variable preprocessor is ready to be integrated into a Scikit-Learn Pipeline for model fitting.
