# House Price Prediction

## Overview

This project utilizes machine learning techniques to estimate house prices based on various property attributes. The dataset includes key features such as house size, number of rooms, and location, which significantly impact market value.

## Dataset

- **train.csv**: Training dataset containing house features and their corresponding sale prices.
- **test.csv**: Testing dataset with house features but without sale prices (to be predicted).
- **House_prediction.csv**: Output file containing predicted house prices for the test dataset.
- **sample_submission.csv**: Example format for submission.
- **House Price Prediction.ipynb**: Jupyter Notebook containing the model implementation.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/1-Satyam/House-Price-Predictions-using-Logistic-Regression.git
   ```
2. Install necessary dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook:
   ```sh
   jupyter notebook "House Price Prediction.ipynb"
   ```
2. Execute the notebook to preprocess data, train the model, and generate predictions.

## Methodology

- **Data Preprocessing**: Handling missing values, outliers, and feature scaling.
- **Feature Engineering**: Selecting and transforming relevant variables.
- **Model Selection**: Evaluating multiple algorithms (e.g., Linear Regression, Random Forest, XGBoost) to determine the best approach.
- **Performance Evaluation**: Using metrics such as Root Mean Squared Error (RMSE) and R² Score to assess model accuracy.

## Contribution

Contributions are welcome! Fork the repository, implement improvements, and submit a pull request.

## License

This project is distributed under the MIT License.
