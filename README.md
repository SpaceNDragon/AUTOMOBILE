# Automobile Fuel Consumption Prediction

This repository is dedicated to predicting city-cycle fuel consumption in miles per gallon for automobiles. The dataset includes both multivalued discrete and continuous attributes, which are described below:

### Attribute Information:

1. mpg: continuous
2. cylinders(cyl): multi-valued discrete
3. displacement(disp): continuous
4. horsepower(hp): continuous
5. weight(wt): continuous
6. acceleration(acc): continuous
7. model year(yr): multi-valued discrete
8. origin: multi-valued discrete
9. car name: string (unique for each instance)

### Project Objective:

The goal of this project is to cluster the data and treat them as individual datasets to train regression models to predict the fuel consumption in miles per gallon (mpg).

### Summary:

Based on the analysis of the dataset, K-means clustering appears to explain the highest variation in the data, with only a 1% difference when compared with other models. However, to gain more clarity and improve accuracy, a larger dataset that includes additional features, such as the number of previous owners, gender of the previous owners, and purpose of the car's usage, may be necessary.

This dataset provides valuable insights into predicting fuel consumption in automobiles, but it is important to note its limitations and the need for additional data to improve the accuracy of the models. Contributions to this repository are welcome, including suggestions for new features or improvements to existing models. 

## Getting Started:

To get started, clone this repository and install the necessary dependencies, including Python 3.x and the required libraries, such as Pandas, NumPy, and Scikit-learn. The Jupyter Notebook included in this repository provides examples of how to preprocess and analyze the data, as well as how to train and evaluate regression models. 

## License:

This repository is licensed under the MIT License. See the `LICENSE` file for more information.
