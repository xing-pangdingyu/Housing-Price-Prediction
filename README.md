# California Housing Price Prediction

This project predicts median house values in California districts using 
the California Housing dataset. It follows the full ML pipeline introduced 
in "Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow" (3rd Edition).

## Dataset
- Source: California Housing dataset (from sklearn.datasets.fetch_california_housing)

## Methods
- Data preprocessing (missing values, scaling, categorical encoding)
- Feature engineering (rooms_per_household, bedrooms_per_room, population_per_household)
- Models: Linear Regression, Decision Tree, Random Forest
- Hyperparameter tuning with GridSearchCV

## Results
- Best RMSE: 50,000 (Random Forest)
- Feature importance: Median Income is the most important predictor

## Future Work
- Try Gradient Boosting / XGBoost
- Incorporate deep learning models
