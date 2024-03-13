# Customer Churn Prediction

This repository contains a machine-learning model for predicting customer churn in the telecom industry.

## Table of Contents
1. [Project Description](#project-description)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Project Description
The project aims to predict customer churn using a machine learning model. The model is trained on a dataset containing various customer attributes and their past behavior. It can help businesses identify customers who are likely to stop using their services, enabling proactive strategies to retain them.

## Features
- **Data Preprocessing**: The script handles missing values, outliers, and categorical variables. It also performs necessary data cleaning tasks.

- **Feature Engineering**: New features are created based on the existing ones to improve the model's predictive power. This includes creating interaction terms, binning numerical variables, and more.

- **Model Training**: The script trains a Random Forest Classifier on the preprocessed data. The model is chosen for its ability to handle a large number of features and its robustness to overfitting.

- **Model Evaluation**: The performance of the model is evaluated using accuracy, precision, recall, and F1 score. Cross-validation is used to get a more reliable estimate of the model's performance.

- **Prediction on New Data**: The trained model can be used to make predictions on new data. The script provides a function to load new data, preprocess it in the same way as the training data, and make predictions using the trained model.


## Installation
1. Clone the repository : <br>
    ```git clone https://github.com/ashroyalc/Machine-Learning.git ```<br>

2. Install the required packages :<br>
   ``` pip install pandas ```

## Contributing
   Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
   MIT



