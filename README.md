🏠 Predicting House Prices - Machine Learning Project




Open In Colab 
Python
Scikit-Learn
Pandas

📌 Overview
This project aims to predict house prices using machine learning regression models. It covers the entire data science pipeline—from data cleaning and exploratory analysis to feature engineering, model training, and evaluation.

📂 Dataset
The dataset contains housing features like:

Location (neighborhood, city)

House size (square footage, number of rooms)

Amenities (garage, garden, etc.)

Sale price (target variable)

(Example datasets: Kaggle's House Prices Dataset or Boston Housing Dataset.)

🛠️ Technologies Used
Python (Pandas, NumPy)

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn

Notebook: Jupyter Notebook / Google Colab

📋 Project Steps
Data Preprocessing

Handling missing values

Removing outliers

Encoding categorical variables

Exploratory Data Analysis (EDA)

Statistical summaries

Correlation heatmaps

Feature distributions

Feature Engineering

Scaling/Normalization

Feature selection (e.g., using SelectKBest)

Model Building

Algorithms Used:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

(Optional) XGBoost / Gradient Boosting

Evaluation Metrics

R² Score (Coefficient of Determination)

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

📊 Results
Model	R² Score	RMSE	MAE
Linear Regression	0.75	45,000	32,000
Random Forest	0.88	28,000	19,000
XGBoost	0.89	26,000	18,000


🚀 How to Run
🚀 How to Run in Google Colab
Open the Notebook:

Click the Open In Colab button above.

Or upload Predicting_House_Prices.ipynb manually to Colab.

Set Up Runtime:

Go to Runtime > Change runtime type and select GPU/TPU (optional for faster training).

Run All Cells:

Use Runtime > Run all or execute cells step-by-step (Shift+Enter).

Data Upload:

If the dataset isn’t auto-loaded, upload it via:


from google.colab import files
files.upload()


![image](https://github.com/user-attachments/assets/836a4a39-37b2-48c1-8953-e36f2dfb4667)

![image](https://github.com/user-attachments/assets/1c262fa7-c73f-46e8-9e6c-77ea776977e6)
![image](https://github.com/user-attachments/assets/c99899c3-282a-4cd4-8730-b2dadf15b733)
