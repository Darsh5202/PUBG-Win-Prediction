# PUBG-Game-Winner-Prediction

Machine Learning project for predicting PUBG player winning performance using gameplay statistics. This project demonstrates complete data preprocessing, exploratory data analysis (EDA), feature engineering, regression model training, and evaluation using multiple regression metrics to predict the player's winning percentage.

# 🎮 PUBG Game Winner Prediction using Machine Learning

## 📌 Project Overview

PUBG (PlayerUnknown's Battlegrounds) is one of the world's most popular battle royale games where player performance depends on various gameplay statistics such as kills, assists, damage dealt, distance traveled, weapons acquired, healing items used, and survival time. This project aims to build a Machine Learning regression model that predicts a player's final winning placement percentage (`winPlacePerc`) based on these gameplay statistics.

The project follows a complete Data Science workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison to identify the most accurate predictive model.

---

## 🎯 Objectives

- Analyze PUBG player performance data.
- Perform comprehensive Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Handle missing values and unnecessary features.
- Perform feature engineering.
- Train regression models to predict player winning percentage.
- Evaluate model performance using regression metrics.
- Select the best-performing model for prediction.

---

## 📂 Dataset Information

The PUBG dataset contains gameplay statistics for thousands of players.

### Features

- Id
- Group ID
- Match ID
- Assists
- Boosts
- Damage Dealt
- DBNOs
- Headshot Kills
- Heals
- Kill Points
- Kills
- Kill Streaks
- Longest Kill
- Match Duration
- Max Place
- Number of Groups
- Rank Points
- Revives
- Ride Distance
- Swim Distance
- Walk Distance
- Weapons Acquired
- Win Points
- Win Place Percentage (Target Variable)

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

- Dataset overview
- Missing value analysis
- Duplicate record detection
- Statistical summary
- Gameplay feature distribution
- Kill analysis
- Distance analysis
- Correlation heatmap
- Target variable analysis
- Outlier detection
- Data visualization

---

## ⚙️ Data Preprocessing

- Data cleaning
- Removing unnecessary identifier columns
- Handling missing values
- Feature engineering
- Feature selection
- Data transformation
- Train-Test Split

---

## 🤖 Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor *(Optional)*
- XGBoost Regressor *(Optional)*

---

## 📈 Evaluation Metrics

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Data Preprocessing
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison
11. Prediction
12. Conclusion

---

## 📌 Results

- Successfully cleaned and preprocessed the PUBG gameplay dataset.
- Performed comprehensive Exploratory Data Analysis (EDA).
- Engineered meaningful gameplay features.
- Trained multiple regression models.
- Evaluated model performance using R² Score, MAE, MSE, and RMSE.
- Built a predictive model for estimating player winning percentage.

---

## ⚠️ Challenges Faced

- Handling a large-scale gameplay dataset.
- Managing highly correlated gameplay features.
- Engineering meaningful features from player statistics.
- Preventing model overfitting.
- Improving prediction accuracy.

---

## 🔮 Future Improvements

- Perform hyperparameter tuning using GridSearchCV.
- Deploy the model using Flask, FastAPI, or Streamlit.
- Build a real-time PUBG performance prediction system.
- Explore deep learning approaches for prediction.
- Integrate live PUBG match statistics.

---

## 👨‍💻 Author

**Darsh Patel**

GitHub: https://github.com/Darsh5202
