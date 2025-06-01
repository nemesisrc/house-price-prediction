# 🏠 House Price Prediction Model 
[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-Latest-green.svg)](https://scikit-learn.org/)

A machine learning model to predict house prices based on various features using Linear Regression and Random Forest algorithms.

## 📊 Project Overview

This project implements a house price prediction model using California housing dataset. The model considers various factors like:
- 📍 Location (latitude, longitude)
- 🏘️ Number of rooms and bedrooms
- 👥 Population and households
- 🌊 Ocean proximity
- 🏪 Housing median age

## 🛠️ Technologies Used

- Python 3.7+
- Libraries:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - scikit-learn

## 🚀 Features

- Data preprocessing and cleaning
- Feature engineering
- Exploratory Data Analysis (EDA) with visualizations
- Implementation of two models:
  - Linear Regression (Score: ~65%)
  - Random Forest Regression (Score: ~80%)
- Correlation analysis using heatmaps
- Geographic visualization of house prices

## 📥 Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```

2. Create and activate virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
```

3. Install required packages
```bash
pip install -r requirements.txt
```

## 📖 Usage

1. Ensure you have Jupyter Notebook installed
2. Open the notebook:
```bash
jupyter notebook house_price_prediction_model.ipynb
```
3. Run all cells sequentially to see the complete analysis and prediction results

## 📁 Project Structure

```
house-price-prediction/
├── house_price_prediction_model.ipynb
├── housing.csv
├── requirements.txt
└── README.md
```

## 📈 Model Performance

- Linear Regression: ~65% accuracy
- Random Forest Regressor: ~80% accuracy

## 🔄 Future Improvements

- [ ] Add more advanced feature engineering
- [ ] Implement cross-validation
- [ ] Try other algorithms (XGBoost, LightGBM)
- [ ] Create a web interface for predictions
- [ ] Add hyperparameter tuning

## 📝 Requirements

Create a `requirements.txt` file with these dependencies:

````python
numpy>=1.19.2
pandas>=1.2.4
matplotlib>=3.3.4
seaborn>=0.11.1
scikit-learn>=0.24.1
jupyter>=1.0.0