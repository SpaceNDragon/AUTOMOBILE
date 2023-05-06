# Automobile Fuel Consumption Prediction

This repository contains data and code related to predicting city-cycle fuel consumption in miles per gallon using machine learning models. The data concerns city-cycle fuel consumption in miles per gallon, and includes 3 multivalued discrete attributes and 5 continuous attributes. 

## Data Description

The data contains the following attributes:

1. mpg: continuous
2. cylinders(cyl): multi-valued discrete
3. displacement(disp): continuous
4. horsepower(hp): continuous
5. weight(wt): continuous
6. acceleration(acc): continuous
7. model year(yr): multi-valued discrete
8. origin: multi-valued discrete
9. car name: string(unique for each instance)

## Project Objective

The objective of this project is to cluster the data and treat them as individual datasets to train regression models to predict "mpg". 

## Getting Started

To get started, clone this repository to your local machine and open the Jupyter notebook provided. The notebook contains the following sections:

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Feature Selection and Scaling
4. Clustering the Data
5. Training Regression Models
6. Model Evaluation and Comparison

The notebook uses Python and popular machine learning libraries such as Scikit-learn and Pandas. Make sure you have these libraries installed before running the notebook.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please submit a pull request.

## License

This repository is licensed under the MIT License. See the `LICENSE` file for more information.
