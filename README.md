# student-performance-prediction
Regression models to predict student exam scores


---

## 🚀 Steps Performed

1. **Data Cleaning**
   - Handled missing values with mode imputation.
   - Encoded categorical variables using `OrdinalEncoder` & `LabelEncoder`.
   - Removed outliers using the IQR method.

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap & distributions plotted.
   - Visualized categorical & numerical features.

3. **Feature Engineering**
   - Applied log transformation on the target variable (`Exam_Score`).

4. **Model Training**
   - Trained **Linear Regression** model.
   - Trained **Polynomial Regression** model (degree=2).

5. **Evaluation Metrics**
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
   - R² Score

---

## 📊 Results Comparison

| Model                 | MAE     | RMSE    | R²       |
|------------------------|---------|---------|----------|
| Linear Regression      | 0.00407 | 0.00489 | 0.98924  |
| Polynomial Regression  | 0.00399 | 0.00477 | 0.98976  |

📌 Polynomial Regression performed slightly better than Linear Regression.

---

## 🔮 Future Improvements
- Try advanced models (Random Forest, XGBoost).
- Hyperparameter tuning.
- Add cross-validation.

---

## 👩‍💻 Author
**Unsa Mariyam**  
BScs Student, Iqra University

