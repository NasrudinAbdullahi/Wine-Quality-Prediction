# 🍷 Wine Quality Prediction - Capstone Project

## 📌 Project Overview
This project aims to develop a **machine learning model** to predict the quality of wine based on its chemical properties. We utilized a dataset from **Kaggle** (insert link here) and applied different preprocessing techniques to clean and analyze the data. Based on our insights, we trained and evaluated **Linear Regression** and **Random Forest Regression** models to determine the most suitable approach for wine quality prediction.

## 📊 Data Source
- **Dataset:** Kaggle (provide link)
- **Features:** Various physicochemical properties such as acidity, alcohol content, pH level, and sulfur dioxide concentration.
- **Target Variable:** Wine quality score (numerical rating).

## 🔍 Data Preprocessing
Before model training, we performed essential data preprocessing steps:
- **Handling Missing Values:** Checked for and addressed any null or missing values.
- **Outlier Detection:** Used statistical methods and boxplots to identify and handle outliers.
- **Exploratory Data Analysis (EDA):** Conducted summary statistics and data visualizations to understand feature distributions.

## 📈 Model Selection
Based on the dataset characteristics and exploratory analysis, we selected and compared:
1. **Linear Regression** - A simple yet effective baseline model.
2. **Random Forest Regression** - A robust ensemble method known for handling complex relationships between features.

## 🚀 Implementation
- Used **Python** with **pandas, NumPy, Matplotlib, Seaborn, and Scikit-Learn**.
- Preprocessed and split the dataset into **training and testing sets**.
- Evaluated models based on **R² score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE)**.
- Fine-tuned hyperparameters for optimal performance.

## 📌 Results & Findings
- The **Random Forest Regression model** outperformed Linear Regression, achieving a higher accuracy in predicting wine quality.
- Key factors influencing wine quality include **alcohol content, volatile acidity, and sulfur dioxide levels**.
- The presence of outliers in sulfur dioxide significantly impacted predictions.

## 🏗️ Future Improvements
- Experimenting with **neural networks** for better generalization.
- Implementing **feature engineering** to enhance model performance.
- Deploying the model using a **web or mobile app** for real-world usability.

## 📁 Repository Structure
```
├── data/               # Raw dataset (not uploaded)
├── notebooks/          # Jupyter notebooks with data analysis & model training
├── src/                # Python scripts for preprocessing & modeling
├── README.md           # Project overview
├── requirements.txt    # Required dependencies
```

## 📜 License
This project is for educational purposes. Feel free to use or modify the code as needed!

---

👨‍💻 **Contributors:** - Vincent Rono, Nasrudin Abdullahi, Maria, Joy

🔗 **Project Link:** [GitHub Repository]

