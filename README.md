# Used Caprice Price Prediction

This is a mini-project created to build a regression model to predict the price of used cars based on various features such as year, kilometers, and condition.

# Techniques utilized in this project:

 - Exploratory Data Analysis (EDA)
 - Data Cleaning
 - Encode Categorical Variables
 - Converted categorical features (e.g., `Trim`, `Lifters_Changed`, `Color`) into numerical representations using `LabelEncoder`.
 - Feature Engineering
 - Train the Model
 - RandomForestRegressor
   
### Evaluate the Model
- Predicted car prices on the test set.
- Evaluated the model's performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
  
###  Cross-Validation with K-Fold
- Implemented 5-Fold Cross-Validation to get a more robust estimate of the model's performance, providing average MAE and RMSE scores across different folds.
  
##  Key Findings
- Feature engineering (e.g., `age`, `km_per_year`) improved the interpretability and predictive power of the model.
- The model achieved a certain MAE and RMSE, and cross-validation provided a more generalized performance estimate.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Kagglehub

- https://www.kaggle.com/datasets/shockinlemon/caprice-dataset
