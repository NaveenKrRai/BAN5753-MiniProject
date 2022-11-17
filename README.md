# BAN5753-MiniProject
## Team - Lamda

### Business Problem:
- The objective of the classification is to identify clients who will subscribe (yes/no) for a term deposit. (Variable y: Target function).
- The Bank wants us to conduct Exploratory Data Analysis (EDA) to identify relationships, and trends in data. For example correlations, bivariate analysis of target versus input variables, facts, univariate patterns, missing data.
- Prescriptive recommendations
- K-means Clustering.
- Compare more than four different supervised algorithms

### DataSet Information:
- Data is about an XYZ bank’s direct marketing campaign. Marketing campaigns were driven by telephone calls.
- Data Set In many cases, more than one contact for the same client was required., in order to access if the product (deposit) would be ('yes') or not ('no') subscribed
- The purpose of the classification is to forecast whether the customer will signup (yes/no) a term deposit (variable y).
- The dataset: XYZ_Bank_Deposit_Data_Classification.csv, 20 entries/columns, sorted by date between May 2008 and November 2010.


### Exploratory Data Analysis:
- Reading the Data
- Renaming few columns
- Summary Statistics of the variables 
- Checking for missing values, which we didn't find in our model
- Summary statistics of the numerical variables
- Checking for Univariate pattern of numeric features
- Correlation between the variables
- Exploring the categorical features
- Checking for Univariate pattern of Categorical features

### Modeling:
- Data split fot training and testing
- Pre-processing and Feature engineering

### Suprived models implementation
To analyse the XYZ's marketing campaign, we ran 4 different models
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Booster
#### Based on our outcomes, we found Gradient Booster as the top performing model for this data set.
