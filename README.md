# HousePricePrediction
Predicting housing prices using linear regression in Python with scikit-learn.


# Housing Price Prediction with Linear Regression

This repository contains a Python script that demonstrates how to predict housing prices using linear regression. The script uses the `scikit-learn` library to train a linear regression model on a dataset of housing prices and lot sizes. The model is then used to predict the prices of new houses based on their lot sizes.

## Dataset

The dataset used in this script is the `Housing.csv` file, which contains the following columns:

* **price:** The price of the house in dollars.
* **lotsize:** The size of the lot in square feet.
* **bedrooms:** The number of bedrooms in the house.
* **bathrms:** The number of bathrooms in the house.
* **stories:** The number of stories in the house.
* **driveway:** Whether the house has a driveway (yes or no).
* **recroom:** Whether the house has a recreation room (yes or no).
* **fullbase:** Whether the house has a full basement (yes or no).
* **gashw:** Whether the house has gas hot water heating (yes or no).
* **airco:** Whether the house has air conditioning (yes or no).
* **garagepl:** The number of garage places in the house.
* **prefarea:** Whether the house is in a preferred area (yes or no).

## Requirements

To run this script, you will need the following libraries:

* **pandas**
* **scikit-learn**
* **matplotlib**
* **numpy**

You can install these libraries using pip:



## Usage

1. Clone this repository to your local machine.
2. Upload the `Housing.csv` file to your Google Colab environment.
3. Run the Python script in Google Colab.

## Results

The script will output a scatter plot of the test data, with the predicted prices shown as a red line. The script will also print the coefficients of the linear regression model.

## License

This project is licensed under the MIT License.
