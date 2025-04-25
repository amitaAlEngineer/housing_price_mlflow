# housing_price_mlflow
This repository contains a machine learning project for predicting housing prices using a Random Forest Regressor. The project uses MLflow for experiment tracking, model logging, and deployment.

# Key Highlights
Trained using GridSearchCV for hyperparameter optimization

Automatically logs best model, hyperparameters, and MSE metric to MLflow

Model is versioned and can be registered for deployment

# 🚀 How to Run
1. Create virtual environment
2. activate virtual environment
3. Install dependencies
   pip install -r requirements.txt
4. Start MLflow UI (for local tracking)
   mlflow ui

   you will get url : http://127.0.0.1:5000

6. Run the each shell of the notebook

# 📊 MLflow Logging Details
Here’s what gets logged to MLflow for each experiment:

✅ Hyperparameters

n_estimators

max_depth

min_samples_split

min_samples_leaf

📈 Performance Metric

mean_squared_error (MSE)

📦 Model Artifact

Saved with mlflow.sklearn.log_model(...)

🏷️ Model Registry (optional if using non-local URI)
![image](https://github.com/user-attachments/assets/8bd9cd26-61f9-436f-943e-f2c5139e055d)


