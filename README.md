🏠 House Price Prediction Using Machine Learning
📌 Project Description

This project implements a Machine Learning regression model to predict house prices using the Boston Housing Dataset available directly in Google Colab. The dataset is preloaded in the Colab environment, allowing seamless execution without manual dataset download.

The system compares multiple regression models and selects the best performing model for accurate price prediction.

🚀 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

📂 Dataset

Source: Preloaded Boston Housing Dataset in Google Colab
Total Records: 506
Features: 13
Target Column: PRICE – Median house price in $1000s

⚙️ Machine Learning Models
Model	Description
Linear Regression	Baseline prediction model
Random Forest Regressor	High-accuracy ensemble model
📊 Model Performance
Metric	Linear Regression	Random Forest
RMSE	~4.8	~2.8
R² Score	~0.75	~0.91
📈 Visualizations

Correlation Heatmap

Actual vs Predicted Price Plot

Feature Importance Graph

📁 Project Structure
House_Price_Prediction/
│
├── house_price_prediction.ipynb
├── README.md
├── requirements.txt

▶ How to Run
Step 1: Open in Google Colab

Upload the notebook house_price_prediction.ipynb into Colab.

Step 2: Run All Cells

Click Runtime → Run All

🔮 Sample Prediction

Input format:

[CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT]

🧠 Key Learning Outcomes

Hands-on regression modeling

Feature scaling techniques

Model evaluation using RMSE and R²

Feature importance interpretation

📌 Conclusion

This project demonstrates how machine learning models can be used to accurately predict housing prices using real-world datasets available directly in Google Colab.

👤 Author

Yash Lokhande
Aspiring Data Analyst / ML Engineer# house-price-predictions-
