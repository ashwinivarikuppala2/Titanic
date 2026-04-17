# Titanic
This project aims to predict whether a passenger survived the Titanic disaster using Logistic Regression. The dataset used is the famous Titanic dataset, which contains passenger information such as age, gender, class, and fare.
This project follows the complete Machine Learning pipeline, including data preprocessing, feature selection, model building, and evaluation.

# 🎯 Project Overview
   Understand the Titanic dataset
   Perform Data Cleaning and Preprocessing
   Conduct Exploratory Data Analysis (EDA)
   Build a Logistic Regression model
   Evaluate model performance
   Make predictions
   
   # Dataset
   Dataset:Titantic dataset(loaded using Seaborn)
   Total record:891 rows*15 columns
   
# 🎯 Features Used for Model
   Pclass
   Sex
   Age
   SibSp
   Parch 
   Fare
   Embarked
   
# Target Variable:
Survived (0 = No, 1 = Yes)

# 🧹 Data Cleaning Steps
   1. Handling Missing Values
    Filled missing values in Age column using mean value
    Filled missing values in Embarked column using mode
    Dropped Cabin column due to too many missing values
   2.Dropping Unnecessary Columns
The following columns were removed:
  PassengerId
  Name
  Ticket
  Cabin

# 🔄 Data Preprocessing
  Categorical columns converted into numerical values:
  Sex → Male = 0, Female = 1
  Embarked → Converted using Label Encoding / One Hot Encoding
  
# Exploratory Data Analysis (EDA)
  Gender vs Survival
  Passenger Class vs Survival
  Age Distribution
  Correlation Heatmap
  
#  Feature Engineering
  Converted categorical data into numerical
  Selected important features
  
# 🤖 Model Building
 Import libraries
 Load dataset
 Data cleaning
 Feature selection
 Train-test split
 Model training
 Model prediction
 Model evaluation
 
# ⚙️ Train Test Split
Dataset split into:
Training data (80%)
Testing data (20%)

# 📈 Results
Model accuracy:0.8048780487804879
Confusion matrix visualized using heatmap

# 📁 Project Structure
Titanic-Logistic-Regression/
│
├── Titanic_Logistic_Regression.ipynb
├── train.csv
├── test.csv
├── README.md

# 🚀 How to Run
Open the notebook in Google Colab / Jupyter Notebook
Run all cells step by step
View analysis, visualizations, and model results
