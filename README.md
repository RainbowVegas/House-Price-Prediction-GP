# House-Price-Prediction-GP

A machine learning project developed as part of **CIS 400**, focused on predicting housing prices using advanced regression techniques and Kaggle datasets. This project explores and compares various regression models to accurately estimate home prices based on a wide range of housing attributes.

## 🚀 Project Overview

This project was designed to apply real-world machine learning practices to the well-known [Kaggle House Prices dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). Our team focused on:

- **Feature engineering** with `pandas` and `scikit-learn`
- **Model selection and tuning**
- **Performance evaluation** using RMSD (Root Mean Squared Deviation)

Final results showed that **CatBoost** provided the best overall accuracy, outperforming other models in both validation and test metrics.

## 🧠 Models Evaluated

We implemented and benchmarked the following regression models:

- Linear Regression
- Lasso Regression
- Ridge Regression
- Random Forest Regressor
- XGBoost Regressor
- **CatBoost Regressor** ✅ *(Best Performer)*

## 📊 Final Performance

The **CatBoost-based model** achieved a **Root Mean Squared Deviation (RMSD) of 0.11**, outperforming all other models in both cross-validation and final evaluation metrics.

## 🔧 Tools & Libraries

- Python 3
- pandas
- numpy
- scikit-learn
- xgboost
- catboost
- matplotlib / seaborn (optional, for EDA)

## 📁 Project Structure

```
House-Price-Prediction-GP/
│
├── data/                # Raw and processed datasets
├── notebooks/           # Jupyter notebooks for EDA and model training
├── models/              # Saved models and results
├── src/                 # Source code and utility scripts
├── README.md            # Project documentation
└── requirements.txt     # Dependencies
```

## 📝 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/House-Price-Prediction-GP.git
cd House-Price-Prediction-GP
```

2. Run the notebooks or scripts inside the `/notebooks` or `/src` directory.

## 📌 Course Info

This project was developed for **CIS 400: Capstone Project**.

## 📜 License

MIT License. See `LICENSE` file for details.

## 🙌 Acknowledgments

- [Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- Open-source contributors for CatBoost, scikit-learn, and XGBoost
