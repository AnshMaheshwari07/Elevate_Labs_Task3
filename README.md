# Elevate_Labs_Task3
1. Import & Preprocess Dataset
Used Titanic dataset.

Selected pclass, age, sibsp, and parch as features and fare as target.

Dropped rows with missing values.

2. Train-Test Split
Used train_test_split() from Scikit-learn (80/20 split).

Ensured reproducibility with a fixed random_state.

3. Fit Linear Regression Model
Trained a LinearRegression model using scikit-learn.

4. Evaluate Model
Used MAE, MSE, and R² metrics to assess model performance.

Evaluated prediction errors and explained variance.

5. Plot Regression Line & Interpret Coefficients
Plotted predicted vs actual values to visualize performance.

Printed model coefficients to interpret how features influence fare.

