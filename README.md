## Diamond Price Prediction
This repository contains a diamond price prediction project for predicting the price of diamonds using the datasets input features : Carat, Depth, Table, x, y, z, Cut, Color and Clarity.


Data set Link : https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv
Dataset Information : Available in EDA under the notebooks folder

This project is a an example of Regression Problem. We have used multiple Regression algorithms and the best algorithm is used for the prediction.

List of models the project uses to train on the dataset -

* Linear Regression
* Lasso
* Ridge
* Elastic Net
* Random Forest
* Decision Tree

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine using the following command:
git clone https://github.com/Sumeetparmar0/DiamondPricePrediction1.git

2. Navigate to the project directory:
cd DiamondPricePrediction1

3. Install the required dependencies using pip:
pip install -r requirements.txt

4. Run the Flask application:
python application.py

5. Open your web browser and go to
http://127.0.0.1:5000/ - to access the home page

http://127.0.0.1:5000/predict - to perform prediction of diamond price on the web application.
