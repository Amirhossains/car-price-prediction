🇬🇧 Project Description (English)
🎯 Project Objective

The goal of this project is to predict car prices based on various factors such as gearbox type, number of seats, ownership history, mileage, and other features.
A real-world dataset obtained from Kaggle was used for this purpose.

🗂 Project Structure

The project consists of three main parts:

Dataset
The original dataset collected from Kaggle

Data Cleaning & Analysis
Data preprocessing, cleaning, and exploratory analysis

Modeling
Feature preparation, model training, and price prediction

🧹 Data Cleaning & Analysis

The following steps were performed:

Removal of columns with no significant impact on car price

Checking for missing (null or blank) values (none were found)

Price analysis based on number of seats, identifying and removing outliers for 4-seat and 8-seat cars

Analysis of price based on ownership history (first, second, third, and fourth owner)

Removal of irrelevant test vehicle records

Analysis of price based on transmission type (manual or automatic) with no detected issues

Analysis of car price vs mileage, visualized using plots

Further optimization was considered out of scope for this project

🤖 Modeling

After data cleaning:

Categorical features were converted into numerical values

The dataset was split into training and testing sets

The following models were trained and evaluated:

Linear Regression

Lasso

Decision Tree Classifier

Based on the evaluation scores, Linear Regression achieved the best performance

Final car price predictions were generated using the Linear Regression model

🛠 Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

📌 Conclusion

Among the tested models, Linear Regression provided the most accurate results for car price prediction.
This project can be further improved by advanced feature engineering, deeper mileage analysis, and more complex models.

👤 Author

Amirhossain
University Machine Learning Project