# 🏠 Housing Price Predictor

A Machine Learning project that predicts California housing prices using Random Forest.

## 📌 About
This project uses the California Housing dataset to train a Random Forest model
that predicts median house values based on features like location, income, and population.

## 🗂️ Project Structure
- `main.py` → Production script (train + inference)
- `main_old.py` → Exploration script (model comparison)
- `housing.csv` → Dataset
- `requirements.txt` → Dependencies

## ⚙️ How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run the project:
   python main.py

- First run → trains and saves the model
- Next runs → loads model and predicts on input.csv

## 🤖 Models Used
- Linear Regression
- Decision Tree Regressor
- ✅ Random Forest Regressor (best performance)

## 🛠️ Tech Stack
- Python
- Scikit-learn
- Pandas
- NumPy
- Joblib
