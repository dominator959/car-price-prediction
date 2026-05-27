# 🚗 Car Price Prediction

A machine learning project to predict used car prices scraped from PakWheels.

## 📁 Project Structure

```
car-price-prediction/
├── data/
│   └── raw/          # Raw scraped data
├── notebooks/
│   ├── 01_data_loading.ipynb
│   ├── 02_data_cleaning.ipynb
│   └── 03_grouping_aggregation.ipynb
├── models/           # Trained model files (gitignored)
├── requirements.txt
└── README.md
```

## 🔧 Setup

```bash
pip install -r requirements.txt
```

## 📓 Notebooks

| Notebook | Description |
|----------|-------------|
| 01_data_loading | Load PakWheels raw data, inspect columns & missing values |
| 02_data_cleaning | Clean and preprocess the dataset |
| 03_grouping_aggregation | Group and aggregate features for analysis |

## 🛠 Tech Stack

Python · Pandas · Scikit-learn · Matplotlib · Seaborn