# House price prediction using ML
This project focuses on predicting house prices using machine learning, specifically the Random Forest Regression model. The model is built and evaluated using Python, with the core libraries being Pandas, Scikit-learn, and Matplotlib.

The project demonstrates a complete workflow, from data preprocessing and feature engineering to model training, evaluation, and deployment. The final model is capable of predicting house prices based on various features such as the number of rooms, location, and other property attributes.

Features
Data Preprocessing:

Handling missing values using different strategies (removal, imputation).
Stratified splitting of data into training and testing sets based on the 'CHAS' feature.
Feature scaling using StandardScaler.
Model Training:

Implementation of a Random Forest Regressor for predicting house prices.
Option to use other models such as Linear Regression and Decision Tree Regressor.
Model Evaluation:

Evaluation using metrics like Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
Cross-validation for better evaluation of model performance.
Pipeline Creation:

Automated data transformation and model training using Scikit-learn's Pipeline.
Model Persistence:

Saving and loading the trained model using joblib.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/krrish1147/House-price-prediction-using-ML.git
cd dragon-real-estate-price-predictor
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the pipeline in Visual Studio Code:

Open the project in Visual Studio Code.
Convert the notebook into a Python script and run the pipeline.
Usage
Training the Model:

The model can be trained using the provided dataset. Preprocess the data and train the Random Forest Regressor model using the pipeline.
Evaluating the Model:

Evaluate the model using cross-validation and calculate RMSE to check its accuracy.
Making Predictions:

Use the trained model to predict house prices for new data points.
The model can be loaded from a saved state and used for prediction.
Testing the Model:

Test the final model on a separate test dataset to evaluate its performance.
Results
The model achieves a good balance between bias and variance, with an acceptable RMSE on both training and test datasets. The feature importance and correlation analysis help in understanding the impact of various features on the house price predictions.

Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.
