# 🏠 House Price Prediction

A Machine Learning project that predicts house prices using three regression models — Linear Regression, Random Forest, and Gradient Boosting — with an interactive web app for real-time predictions.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

This project builds and compares multiple machine learning models to predict house prices based on features like size, location, number of bedrooms, and more. It includes full EDA, model training, evaluation, and an interactive prediction interface.

---

## 🎯 Models Used

| Model | R² Score | RMSE | MAE |
|-------|---------|------|-----|
| Linear Regression | 95.9% | $20,608 | $16,631 |
| Gradient Boosting | 95.3% | $21,921 | $17,634 |
| Random Forest | 93.9% | $25,087 | $19,987 |

✅ **Best Model: Linear Regression** with **95.9% R² accuracy**

---

## 📂 Project Structure

```
house-price-prediction/
│
├── House_Price_Prediction.ipynb   # Main notebook (EDA + Models)
├── house_prices.csv               # Dataset
├── requirements.txt               # Dependencies
└── README.md                      # Documentation
```

---

## 📊 Features Used

| Feature | Description |
|---------|-------------|
| `Bedrooms` | Number of bedrooms |
| `Bathrooms` | Number of bathrooms |
| `SqftLiving` | Total living area (sq ft) |
| `HouseAge` | Age of the house (years) |
| `Garage` | Number of garage spaces |
| `Floors` | Number of floors |
| `Neighborhood` | 0=Budget, 1=Standard, 2=Premium, 3=Luxury |
| `DistanceToCity` | Distance from city center (km) |

---

## 🔍 Key Insights

- **SqftLiving** is the most important feature — contributes 62% to prediction
- **Neighborhood** quality has the second highest impact at 17%
- **Distance to city** negatively affects price — farther = cheaper
- **House Age** reduces price — older houses cost less
- All 3 models achieved R² scores above 93%

---

## 🛠️ Technologies Used

- Python 3.10
- Pandas & NumPy — data manipulation
- Matplotlib & Seaborn — visualization
- Scikit-learn — machine learning models
- Jupyter Notebook — development environment

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook House_Price_Prediction.ipynb
```

4. Run all cells from top to bottom

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-linkedin](https://linkedin.com/in/your-linkedin)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
