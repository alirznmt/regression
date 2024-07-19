# Regression Model Implementation

## Overview
This project involves implementing linear regression and polynomial regression models, and learning their parameters using Stochastic Gradient Descent (SGD) and direct matrix formula. The Weather in Szeged 2006-2016 dataset is used, with 96453 samples and 6 features. The target variable is Temperature (C).

## Dataset
The dataset used is the Weather in Szeged 2006-2016 dataset, available on the Elearn website. The features are:
- Apparent Temperature (C)
- Humidity
- Wind Speed (km/h)
- Wind Bearing (degrees)
- Visibility (km)
- Pressure (millibars)

The target is Temperature (C). 

## Project Steps
1. **Exploratory Data Analysis**:
   - Provide scatter plots and descriptive displays for each feature.
   - Standardize the data and add a constant 1 column to the features matrix for the bias term.

2. **Linear Regression (Direct Approach)**:
   - Implement a direct approach using normal equations to obtain the linear regression solution.
   - Save and report the required running time.

3. **Mini-Batch Stochastic Gradient Descent**:
   - Implement a mini-batch stochastic gradient descent approach to obtain the linear regression solution.
   - Use batch sizes of {10, 20, 30, 40, 50, 100}.
   - Iterate over the data, updating weights with each mini-batch.
   - Report the error obtained for each batch size and identify which batch size gives the best result on the test data.

4. **Polynomial Regression**:
   - Implement polynomial regression with a p = 2 degree polynomial using the mini-batch stochastic gradient descent approach.
   - Report the error obtained by the polynomial regression model.

5. **General M-th Order Polynomial Regression** (Optional):
   - Implement a general M-th order polynomial regression model.
   - Report the best polynomial regression model for the dataset.

6. **AdaGrad Algorithm**:
   - Use the AdaGrad algorithm on the step-size approach for the linear regression model.
   - Report the error obtained.

7. **Momentum Algorithm** (Optional):
   - Use the Momentum algorithm on the SGD with the same number of epochs as the linear regression model.
   - Report the error and convergence speed.

8. **Comparison with Python Packages**:
   - Use packages like `statmodels` and `sklearn` to do regression modeling.
   - Compare results on linear regression (part 1) with written tools and packages.
   - Report pros and cons of custom functions versus built-in ones, focusing on running time and accuracy.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, scikit-learn, statmodels

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter notebook or Python scripts provided.

## Results
- Running time and accuracy for the direct approach and mini-batch SGD.
- Errors for different batch sizes.
- Errors for polynomial regression models.
- Comparison of results using AdaGrad and Momentum algorithms.
- Comparison with results from Python packages.

## Conclusion
This project demonstrates the implementation of regression models using different approaches and algorithms, providing insights into their performance and efficiency.


