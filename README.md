# 🏡 Housing Price Prediction using Linear Regression

This project demonstrates a machine learning approach to predict housing prices based on several independent variables using **Linear Regression**. The model is trained on a clean housing dataset and aims to predict prices with good accuracy using statistical learning techniques.

---

## 📌 Project Description

The goal of this project is to:
- Understand the relationship between house features and price.
- Build a linear regression model using `scikit-learn`.
- Evaluate the model's performance using metrics such as **R² Score**, **MAE**, and **RMSE**.
- Visualize key insights and relationships from the dataset.

---

## 📊 Dataset Description

The dataset used is `Housing.csv`, which contains the following features:

| Column Name | Description                         |
|-------------|-------------------------------------|
| price       | Selling price of the house (target) |
| area        | Total area in square feet           |
| bedrooms    | Number of bedrooms                  |
| bathrooms   | Number of bathrooms                 |
| stories     | Number of floors                    |
| mainroad    | Whether there is a main road access |
| guestroom   | Availability of guest room          |
| basement    | Whether it has a basement           |
| hotwaterheating | Availability of hot water system |
| airconditioning | Has air conditioning or not      |
| parking     | Number of parking spaces            |
| prefarea    | Whether it's a preferred area       |
| furnishingstatus | Furnishing status (furnished/semi/unfurnished) |

---

## 🧾 Project Structure:

housing-price-prediction-linear-regression/
│

├── Housing.csv # Dataset

├── housing-price-prediction.ipynb # Main Notebook

├── requirements.txt # Dependencies

└── README.md # Project Overview

yaml
Copy
Edit

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/housing-price-prediction-linear-regression.git
cd housing-price-prediction-linear-regression
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook housing-price-prediction.ipynb
```
✅ Requirements
You can install all necessary packages using the requirements.txt file.

📈 Visualizations
The notebook includes:

Correlation heatmap

Distribution of house prices

Scatter plots of features vs. target

Residual plots for regression evaluation

🧠 Model Performance
The Linear Regression model was evaluated using:

R² Score

Mean Absolute Error

Root Mean Squared Error

🙋‍♂️ Author

Safal Swayam

Master's in Computer Applications (KIIT)
