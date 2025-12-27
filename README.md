# 🚗 Car Price Predictor (Flask + Machine Learning)

A web-based Machine Learning application that predicts the resale price of a car based on key attributes such as company, model, year of purchase, fuel type, and kilometres driven.

The project uses **Flask** for the backend, **scikit-learn** for model training, and a **Pipeline with ColumnTransformer & OneHotEncoder** for preprocessing categorical features.

---

## 📌 Features

- Predicts car resale price instantly
- User-friendly web interface
- Trained using Linear Regression with proper preprocessing
- Handles unseen categorical values safely
- Ready for deployment

---

## 🛠 Tech Stack

- **Python**
- **Flask**
- **Pandas, NumPy**
- **scikit-learn**
- **HTML, CSS, Bootstrap**
- **AJAX (XMLHttpRequest)**

---

## 📂 Project Structure

Car_Price_Predictor/
│
├── app.py
├── LinearRegressionModel.pkl
├── Cleaned_Car_data.csv
├── README.md
│
├── templates/
│ └── index.html
│
├── static/
│ └── css/
│ └── style.css
│
└── myenv/ (virtual environment)


🌐 Flask Backend (app.py)

The Flask app:

Loads the trained model

Accepts form data from UI

Converts input into a Pandas DataFrame

Returns the predicted price

Key requirement:

The input DataFrame must exactly match the feature names used during training:

Create Virtual Environment
python -m venv myenv
myenv\Scripts\activate   # Windows


👨‍💻 Author

Saurabh Srivastava
Data Analyst | Machine Learning Enthusiast
