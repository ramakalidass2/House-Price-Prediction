# House-Price-Prediction
Regression model to predict house prices using the California Housing dataset
# 🏠 California House Price Prediction (Regression Model)

This project builds a **linear regression model** to predict house prices using the **California Housing dataset** from Scikit-learn. The goal is to estimate the median house value in California districts based on factors like income, housing age, and average rooms.

---

## 📂 Dataset

- **Source**: [Scikit-learn California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
- **Records**: 20,640 entries
- **Features**:
  - `MedInc` – Median income
  - `HouseAge` – Median house age
  - `AveRooms` – Average number of rooms
  - `AveOccup` – Average occupancy
  - `Latitude` & `Longitude` – Geographic location
  - `MedHouseVal` – Median house value (target)

---

## 📊 Workflow

1. **Data Loading**  
   Using Scikit-learn's `fetch_california_housing()` with `as_frame=True` to get a pandas DataFrame.

2. **Exploratory Data Analysis (EDA)**  
   - Data types, missing values
   - Correlation heatmap
   - Scatterplots & distribution plots

3. **Feature Selection**  
   - Selected top features most correlated with target value

4. **Modeling**  
   - Linear Regression from Scikit-learn
   - Train-test split (80/20)
   - Evaluation metrics: MAE, MSE, RMSE, R² Score

5. **Visualization**  
   - Actual vs Predicted plot
   - Price distribution

---

## 🤖 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 📈 Model Performance

| Metric      | Score                 |
|-------------|-----------------------|
| MAE         | 0.6015701115985254    |
| MSE         | 0.6561369372393887    |
| RMSE        | 0.8100228004441533    |              
| R² Score    | 0.4992884296930027    |

---

## 📌 License

This project is for educational purposes only.

---

