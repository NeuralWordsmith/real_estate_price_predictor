# Real Estate Price Predictor

This project demonstrates a complete machine learning pipeline for predicting house prices using the Ames Housing dataset. It involves data preprocessing, exploratory data analysis, model training, evaluation, hyperparameter tuning, and visualizations.

## Features

- Load and preprocess housing data
- Train Linear Regression, Random Forest, and XGBoost models
- Evaluate models using MAE and RMSE
- Tune hyperparameters using GridSearchCV
- Visualize predicted vs. actual prices
- Display feature importance for the XGBoost model

## Instructions

### Requirements

Ensure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

Install all dependencies using:

```bash
pip install -r requirements.txt
```

### Running the Project

1. Place `train.csv` in the project directory (already included).
2. Open the notebook `Real_Estate_Price_Predictor_Project.ipynb` in Jupyter Notebook or VS Code.
3. Run the notebook step by step to train and evaluate the models.
4. Review the visualizations saved as `actual_vs_predicted.png` and `feature_importance.png`.

## File Structure

- `train.csv` — Housing dataset from Kaggle
- `Real_Estate_Price_Predictor_Project.ipynb` — Main notebook
- `actual_vs_predicted.png` — Predicted vs. actual price plot
- `feature_importance.png` — Top features used in model prediction
- `requirements.txt` — List of required Python packages

## License

This project is licensed under the MIT License.
