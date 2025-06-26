🏡 Task 3: Linear Regression – House Price Prediction

📌 Objective

To implement and understand simple and multiple linear regression using Scikit-learn for predicting house prices based on various features.


---

🛠 Tools & Libraries Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn



---

📂 Dataset

Name: Housing.csv
Preview:
The dataset contains features like area, number of bedrooms, bathrooms, stories, presence of main road, guestroom, basement, air conditioning, parking, furnishing status, etc., with target variable price.


---

🚀 Project Workflow

1. Data Import and Preprocessing

Loaded dataset using pandas.

Converted categorical variables like yes/no to 1/0.

Used one-hot encoding (pd.get_dummies) for multi-category features.


2. Train-Test Split

Used train_test_split() with 80-20 split.


3. Model Training

Trained a multiple linear regression model using LinearRegression() from sklearn.linear_model.


4. Model Evaluation

Evaluated model on test set using:

Mean Absolute Error (MAE): 970043.40

Mean Squared Error (MSE): 1754318687330.66

R² Score: 0.6529


5. Visualization

Scatter plot of actual vs predicted prices

Regression line for visual reference



---

📈 Output Plot

📌 Actual vs Predicted House Prices

Blue dots represent predicted vs actual

Red dashed line is the ideal fit (perfect prediction)



---



🧠 Concepts Practiced

Data preprocessing

One-hot encoding

Linear regression using Scikit-learn

Regression evaluation metrics

Data visualization and interpretation

[click here to view the output]
https://github.com/DeekshithaRM/Task_3/blob/main/Linear_Regression_Task_3_Output.pdf
