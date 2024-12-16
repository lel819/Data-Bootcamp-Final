# Data-Bootcamp-Final

Project Overview
This project aims to predict the Total Stats of Pokémon using multiple regression models, including:
- Linear Regression
- K-Nearest Neighbors (KNN) Regression
- Decision Tree Regression
- Random Forest Regression

Through detailed exploratory data analysis (EDA), model implementation, and evaluation, this project identifies the most effective regression model for predicting Pokémon Total Stats based on numeric and categorical features.

Dataset
The dataset used is the Pokémon Dataset containing 800 rows and 13 columns

Source: Kaggle's Pokémon Dataset.
Key Features (I onlys used 10 columns in this analysis):
- Name: Name of the Pokémon
- Type 1 and Type 2: Categorical features indicating Pokémon types
- HP, Attack, Defense, Sp. Atk, Sp. Def, and Speed: Core numerical stats
- Total: Sum of all stats (target variable)
- Generation: Generation the Pokémon belongs to
- Legendary: Boolean flag indicating Legendary Pokémon

Project Workflow
Exploratory Data Analysis (EDA)
- Analyzed the dataset structure, missing values, and distributions
- Visualized relationships between Pokémon stats and features

Data Preprocessing
- Categorical Encoding: One-Hot Encoding for Type 1 and Type 2
- Train-Test Split: 80/20 split for training and testing the models

Regression Models
- Linear Regression 
- KNN Regression
- Decision Tree Regression
- Random Forest Regression

Model Evaluation
- Mean Squared Error (MSE)
- R² Score

Feature Importance
- Used Permutation Importance and model coefficients to identify key features influencing Total Stats

Key Results
- Best Model: Linear Regression achieved the highest generalizability with the lowest error metrics
- Random Forest performed well but showed signs of overfitting compared to Linear Regression

Feature Importance:
- Special Attack (Sp. Atk), Defense, Speed, and HP were the most important predictors of Total Stats
- Type 1 and Type 2 (categorical features) had negligible influence
