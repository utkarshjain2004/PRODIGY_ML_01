# House Price Prediction using Linear Regression

## Project Overview

This project is the first task of my machine learning internship, where I implemented a linear regression model to predict house prices based on key features such as square footage, number of bedrooms, and number of bathrooms.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Model](#model)
- [Results](#results)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Dataset

The dataset used in this project includes house prices along with features such as square footage, number of bedrooms, and number of bathrooms. The dataset was preprocessed to handle missing values and outliers.

## Features

The features used in the model are:

- **Square Footage**: The total area of the house in square feet.
- **Number of Bedrooms**: The total number of bedrooms in the house.
- **Number of Bathrooms**: The total number of bathrooms in the house.

## Model

A linear regression model was implemented to predict the house prices. The steps involved in creating the model were:

1. **Data Preprocessing**: Cleaning the dataset and handling missing values.
2. **Feature Engineering**: Selecting and preparing the features for the model.
3. **Model Training**: Training the linear regression model on the dataset.
4. **Model Evaluation**: Evaluating the model's performance using appropriate metrics.

## Results

The linear regression model achieved promising results with a good level of accuracy in predicting house prices. Key performance metrics include:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R-squared (R²) score**

## Conclusion

This project provided valuable insights into the factors affecting house prices and demonstrated the effectiveness of linear regression in predictive modeling. The experience gained through this task has solidified my understanding of regression analysis and its real-world applications.

## Installation

To run this project locally, please follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd house-price-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To train and evaluate the model, run the following command:
```bash
python train_model.py
```

Ensure that you have the dataset in the correct format and location as specified in the code.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
