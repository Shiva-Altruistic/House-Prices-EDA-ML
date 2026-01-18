# House-Prices-EDA-ML
🔹 Problem Statement

Predict house sale prices based on various features such as size, quality, location, and year built.

🔹 Dataset

Source: Kaggle House Prices competition

Training data: 1460 rows, 81 features

Target variable: SalePrice

1️⃣ Exploratory Data Analysis (EDA)

Studied distribution of SalePrice

Identified right skew → applied log transformation

Analyzed numerical and categorical features

Checked correlations with target

2️⃣ Data Cleaning

Handled missing values:

Categorical missing → filled with "None"

Numerical missing → filled with median or group median

Verified no missing values remained

3️⃣ Feature Encoding

Ordinal features (quality-related) → label encoding

Nominal features → one-hot encoding

Aligned train and test datasets

4️⃣ Model Development

Used Ridge Regression as baseline model

Applied log transformation on target (log1p)

Trained model on processed features

5️⃣ Prediction & Evaluation

Evaluated using RMSE on the validation set

Converted predictions back using expm1

Generated submission file for Kaggle

🔹 Model Used

Ridge Regression

Reason: Handles multicollinearity and works well as baseline

🔹 Tools & Libraries

1. Python

2. Pandas, NumPy

3. Matplotlib, Seaborn

4. Scikit-learn

🔹 Result

Achieved a strong baseline RMSE score

The model is ready for further improvement using advanced techniques
