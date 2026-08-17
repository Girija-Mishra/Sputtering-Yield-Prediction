# Sputtering Yield Prediction Using Machine Learning

## Project Overview

This project uses Machine Learning to predict sputtering-related particle behavior from plasma-material interaction simulation data.

The main goal is to reduce the dependency on computationally expensive simulations by using Machine Learning models for fast prediction.

## Dataset

The dataset contains simulation data for different:

* Ion species
* Target materials
* Ion energies
* Ion mass and target mass
* Mass ratio
* Reduced mass
* Nuclear stopping
* Electronic stopping

The main target variable is **BS_N (Number Backscattering Coefficient)**.

The final dataset contains approximately **1,272 data points**.

## Models Used

* Linear Regression
* Polynomial Regression
* Random Forest Regressor
* Physics-Informed MLP using PyTorch

## Results

| Model                 | R² Score |
| --------------------- | -------: |
| Linear Regression     |   0.8704 |
| Polynomial Regression |   0.3895 |
| Random Forest         |   0.9993 |
| Physics-Informed MLP  |   0.9924 |

Random Forest achieved the highest R² score, while the Physics-Informed MLP also achieved strong predictive performance.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* PyTorch
* Jupyter Notebook

## Project Workflow

Simulation Data → Data Preprocessing → Feature Engineering → Model Training → Model Evaluation → Prediction

## Future Improvements

* Increase the dataset size
* Add more physical constraints to the neural network
* Test additional ML and Deep Learning models
* Validate predictions with additional simulation or experimental data

## Author

**Girija Kumari Mishra**

B.Tech – Computer Science and Engineering
