Project: Data Cleaning & Preprocessing — Titanic Dataset

Steps Performed:

1. Loaded dataset and explored using head(), info(), describe().

2. Handled missing values
     Age → filled with median
     Embarked → filled with mode
     Cabin → dropped (too many missing values)

3. Encoded categorical variables
     One-Hot Encoding for Sex, Embarked

4. Converted boolean columns to numeric (0/1).

5. Detected outliers using boxplots (Age, Fare).

6. Handled Fare outliers using IQR-based winsorization.

7. Scaled numeric features using StandardScaler.

8. Saved the cleaned dataset as titanic_cleaned.csv.