# Multiple Linear Regression Example

## Overview

This project is a school exercise designed to help students learn how to implement a multiple linear regression model using various Python libraries. The Computer Hardware dataset is used to compare the results obtained with those presented in the article "Attributes of the Performance of Central Processing Units: A Relative Performance Prediction Model".

## Description

In this work, different Python libraries are implemented to calculate a linear regression model. The goal is to compare the results obtained with those presented in the aforementioned article.

### Results

In the calculated linear regression model, the following points can be observed:

- **Coefficients**: The coefficients "MAVG", "CACH", "CHCAP", and "Intercept" correspond to the values of beta0, beta1, beta2, and beta3 of the multiple linear regression model. These values are very close to those calculated in the aforementioned article.
- **Probability Value**: The probability value for all coefficients is 0.000. With a significance level of 0.005%, there is significant evidence to reject the null hypothesis (H0). Therefore, there is a strong correlation of the variables.
- **Coefficient Ranges**: With 95% confidence, it is observed that the true values of these coefficients are within this range. For example, the value of "Intercept" is in the range [3.778 - 3.791].
- **Correlation Coefficient**: The correlation coefficient "r" is 1, which means there is a strong positive correlation.

## Usage

1. Clone this repository to your local machine.
2. Open the `book_example_linear_regression.ipynb` file in Jupyter Notebook or any other compatible environment.
3. Execute the cells in the notebook to calculate the linear regression model and observe the results.

## Dependencies

This project requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `statsmodels`

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using pip:
    ```sh
    pip install numpy pandas matplotlib statsmodels
    ```

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or inquiries, please contact Juan José Solórzano Carrillo at [juanjose.solorzano.c@gmail.com](mailto:juanjose.solorzano.c@gmail.com).
