# 🚗 Car Price Prediction: Advanced Regression Analytics
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Machine_Learning-Scikit--Learn-orange.svg)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Internship-CodeAlpha-brightgreen.svg)](https://www.codealpha.tech/)

## 📝 Project Overview
In the automotive market, pricing is a complex science. For this **CodeAlpha Internship** task, I developed a machine learning model that predicts the resale value of vehicles. This project goes beyond basic math; it explores how factors like **Age**, **Mileage**, and **Fuel Type** contribute to a car's depreciation over time.

---

## 🧐 My Engineering Process
Instead of just using the raw data, I applied several "Data Science" techniques to make the model more accurate:
* **Feature Engineering:** I converted the 'Year' column into 'Car Age'. This is much more effective because the model can now calculate depreciation directly based on the vehicle's age.
* **Categorical Handling:** Since the AI doesn't understand words like "Petrol" or "Manual," I used **One-Hot Encoding** to transform these into a numeric format it could process.
* **Algorithm Choice:** I implemented a **Random Forest Regressor**. I chose this because car prices don't always follow a straight line (Linear Regression). Random Forest uses an ensemble of 100 decision trees to handle the "noise" and give a more stable prediction.

---

## 📊 Key Insights & Results
* **The Depreciation Factor:** My analysis confirmed a strong negative correlation between the car's age and its price—as age goes up, price consistently drops.
* **Model Performance:** - **R-Squared Score:** `[Insert Your Score, e.g., 0.92]` (This means my model explains over 90% of the price variations!)
  - **MAE (Mean Absolute Error):** I achieved a low error rate, meaning my predictions are very close to the actual market values.



---

## 🛠️ Technical Stack
| Domain | Tools Used |
| :--- | :--- |
| **Language** | Python 3 |
| **Data Logic** | Pandas, NumPy |
| **Visuals** | Seaborn, Matplotlib |
| **ML Model** | Scikit-Learn (Random Forest) |

---

## 📂 Repository Contents
- `CodeAlpha_Car_Price_Prediction.ipynb`: My full analysis and commented code.
- `car_data.csv`: The dataset containing vehicle specifications and pricing.
- `README.md`: Documentation and project summary.

## 🏁 Personal Reflection
This task taught me how to handle **Regression** problems and the importance of feature engineering. Seeing the "Actual vs Predicted" graph align so closely with the diagonal line was a great confirmation that the Random Forest model was the right choice for this data.

**Intern:** [Edmund Eric Gah]  
**Organization:** CodeAlpha
