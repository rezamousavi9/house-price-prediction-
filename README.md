# 🏠 House Price Prediction using XGBoost

A machine learning project that predicts California house prices using the XGBoost Regressor algorithm. This project demonstrates a complete regression workflow, from loading the dataset to training, evaluating, and making predictions.

---

## 📌 Project Overview

This project uses the California Housing Dataset provided by Scikit-learn to build a house price prediction model.

The workflow includes:

- Loading the dataset
- Data preprocessing
- Exploratory data analysis (EDA)
- Train/Test split
- Model training using XGBoost Regressor
- Model evaluation
- House price prediction

---

## 📊 Dataset

The project uses the California Housing Dataset available in Scikit-learn.

The dataset is downloaded automatically using:
from sklearn.datasets import fetch_california_housing

Dataset information:

- 20,640 samples
- 8 numerical features
- Target variable: Median house value

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🚀 Installation

Clone the repository:
git clone https://github.com/rezamousavi9/house-price-prediction-.git

Move into the project directory:
cd house-price-prediction-

Install the required packages:
pip install -r requirements.txt

Launch Jupyter Notebook:
jupyter notebook

Open the notebook and run all cells.

---

## 📁 Project Structure
house-price-prediction/
│
├── house_price_prediction.ipynb
├── requirements.txt
├── README.md
└── .gitignore

---

## 📈 Model

The project uses XGBoost Regressor, a gradient boosting algorithm known for its high performance on structured/tabular datasets.

The model is trained on the California Housing Dataset and evaluated using regression metrics.

---

## 📚 Python Libraries

- pandas
- numpy
- matplotlib
- scikit-learn
- xgboost

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Feature importance visualization
- Model comparison with Linear Regression and Random Forest
- Model deployment using Streamlit
- Interactive prediction interface

---
## 📊 Results

Model: XGBoost Regressor

Evaluation Metrics:

- R² Score:0.84
- Mean Absolute Error (MAE):0.31
  
## 👨‍💻 Author

Reza Mousavi

GitHub: https://github.com/rezamousavi9
