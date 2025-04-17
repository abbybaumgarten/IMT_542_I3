# 🌍 GDP Predictor App 

This is a simple machine learning application that predicts a country’s GDP per capita based on features like **life expectancy**, **population**, and **literacy rate** using data from the World Indicators dataset.

---

## 📈 Features

- Loads and cleans real-world indicator data
- Trains a linear regression model using `scikit-learn`
- Visualizes:
  - Actual vs Predicted GDP per capita
  - GDP vs individual features (with regression trendlines)
- Makes custom predictions based on user input

---

## 📁 Files in This Repository

| File Name                    | Description                              |
|-----------------------------|------------------------------------------|
| `GDP_Predictor.ipynb`       | Main Python notebook (Google Colab)      |
| `cleaned_world_indicators.csv` | Cleaned dataset used for training        |
| `actual_vs_predicted_gdp.png` | Visualization of model performance       |
| `gdp_vs_features.png`       | Scatter plots of GDP vs key features     |
| `README.md`                 | This documentation                       |

---

## 🚀 How to Use

1. **Clone or download** this repo to your local machine

2. **Install Python libraries** (if not using Colab):

   ```bash
   pip install pandas matplotlib seaborn scikit-learn
