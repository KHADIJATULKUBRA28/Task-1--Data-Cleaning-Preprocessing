📘 Titanic Data Cleaning & Preprocessing

This project performs data cleaning and preprocessing on the Titanic dataset.
It follows a complete machine-learning preprocessing workflow including:

🔍 Steps Performed
1. Data Loading & Exploration
   Loaded the Titanic dataset using Pandas
   Viewed structure using head(), info(), describe()
   Identified missing values
2. Handling Missing Values
   Age → filled using median
   Embarked → filled using mode
   Cabin → dropped due to too many missing values
3. Encoding Categorical Variables
   Converted Sex and Embarked into numeric form using One-Hot Encoding
4. Outlier Detection & Treatment
   Plotted boxplots for Age and Fare
   Kept Age outliers (valid values)
   Capped extreme Fare outliers using IQR-based winsorization
5. Feature Scaling
   Standardized numerical features (Age, Fare, SibSp, Parch, Pclass) using StandardScaler
6. EDA Visualizations
   Histograms
   Boxplots
   Correlation heatmap
7. Saving Cleaned Dataset
   Exported cleaned dataset as:
   titanic_cleaned.csv

📁 Files in this Repository

data_cleaning_preprocessing.ipynb — Complete notebook
Titanic-Dataset.csv — Original dataset
titanic_cleaned.csv — Fully cleaned dataset
README.md — Project summary

🧰 Tools & Libraries Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

This project demonstrates essential skills for machine learning preprocessing:
cleaning, encoding, outlier handling, scaling, and exploratory data analysis.
It prepares the dataset for use in classification models such as Logistic Regression or Random Forest.
