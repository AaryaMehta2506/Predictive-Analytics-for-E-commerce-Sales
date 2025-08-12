Data Analytics Intermediate Project
# Predictive Analytics for E-commerce Sales

## 📌 Overview
This project focuses on using **predictive analytics** to forecast e-commerce sales based on various features such as price, discount, marketing spend, and seasonal factors (year/month).  
We compare **Linear Regression** and **Random Forest Regressor** models to determine the best approach and analyze feature importance for business insights.

---

## 📂 Dataset
The dataset contains:
- **Date**: Transaction date
- **Product_Category**: Category of the product
- **Price**: Price of the product
- **Discount**: Discount offered
- **Customer_Segment**: Customer type (Premium, Occasional, etc.)
- **Marketing_Spend**: Marketing budget spent
- **Units_Sold**: Number of units sold

📌 *Note*: In preprocessing, we extract **Year** and **Month** from the `Date` column for seasonality analysis.

---

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn (LinearRegression, RandomForestRegressor)
- SimpleImputer (handling missing values)

---

## 🚀 Steps Performed
1. **Data Loading & Exploration**
2. **Data Cleaning & Preprocessing**
   - Date parsing
   - Extracting Year & Month
   - Handling missing values with `SimpleImputer`
3. **Feature Selection**
4. **Model Training**
   - Linear Regression
   - Random Forest Regressor
5. **Model Evaluation**
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score
6. **Feature Importance Analysis** (Random Forest)
7. **Visualization** of important features

---

## 📈 Results
- **Random Forest** generally outperformed **Linear Regression** in prediction accuracy.
- **Price** and **Marketing Spend** emerged as top drivers of sales.
- Seasonal patterns were captured using Year and Month features.

---

## 📊 Sample Output
Linear Regression Performance:
MAE: 3.45
RMSE: 4.12
R² Score: 0.78

Random Forest Performance:
MAE: 2.10
RMSE: 3.05
R² Score: 0.92

---

## 📌 How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
python main.py
```
---

## 🤝 Contributing
Contributions are welcome!
Feel free to fork the repository, improve the game, and open a pull request. Let's grow this classic game together!

---

## 📄 License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

---

## 👩‍💻 Author
**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)


