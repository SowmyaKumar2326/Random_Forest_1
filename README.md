# Random_Forest_1
Random forest is a commonly-used machine learning algorithm trademarked by Leo Breiman and Adele Cutler, which combines the output of multiple decision trees to reach a single result. Its ease of use and flexibility have fueled its adoption, as it handles both classification and regression problems.
This document outlines the end-to-end process of analyzing a dataset from a cloth manufacturing company. The primary objective is to check how the sales are going on , with the 'Sales' column as the dependent variable and the remaining columns as independent variables.
Data Preprocessing:Importing Necessary Packages and Extracting Data
Importing Necessary Packages and Extracting Data:The initial step involved importing essential Python packages and extracting the company data.
Handling Missing Values and Encoding Categorical Data:Three columns with categorical data were converted into numerical format using label encoding. Some missing values were detected and filled.

## Exploratory Data Analysis (EDA)
EDA was conducted to understand relationships between different variables. A heatmap was used for correlation analysis, and boxplots aided in identifying outliers.
Outlier Detection and Imputation:Outliers were detected using boxplots, and imputation was performed using threshold values to maintain data integrity.
Save Cleaned Data:The cleaned data was saved separately for future use.

## Modeling:
Data Splitting and Scaling:The 'Sales' column was set as the dependent variable (y), and the rest of the columns were used as independent variables (X). The data was scaled using Standard Scaler, and a train-test split of 80:20 was performed.
Random Forest Classifier:The data was fitted into a Random Forest classifier to predict the 'Sales' column for the test set.
Model Evaluation:The model was evaluated for accuracy by predicting 'Sales' values for the test set. The entire process was repeated with different times with different random states, resulting in an overall accuracy of 81.25%.
## Conclusion
The project successfully analyzed the cloth manufacturing company's dataset to predict the high sale. Through careful preprocessing, exploratory data analysis, and the implementation of a Random Forest classifier, the model achieved a high accuracy rate of 81.25%.

