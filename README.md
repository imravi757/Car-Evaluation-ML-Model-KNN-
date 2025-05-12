# Car Evaluation Prediction Model

## Overview
This project implements a machine learning model to evaluate and predict car acceptability based on various features like buying price, maintenance cost, number of doors, seating capacity, luggage boot size, and safety rating. The model uses the K-Nearest Neighbors (KNN) algorithm to classify cars into four categories: unacceptable, acceptable, good, and very good.

## Dataset
The dataset used in this project is the "Car Evaluation" dataset from the UCI Machine Learning Repository. It contains the following attributes:

- **buying**: Buying price (vhigh, high, med, low)
- **maint**: Maintenance price (vhigh, high, med, low)
- **doors**: Number of doors (2, 3, 4, 5more)
- **persons**: Seating capacity (2, 4, more)
- **lug_boot**: Luggage boot size (small, med, big)
- **safety**: Safety rating (low, med, high)
- **class**: Car acceptability (unacc, acc, good, vgood)

## Features
- Data preprocessing using LabelEncoder to convert categorical data to numerical values
- K-Nearest Neighbors classifier with k=7
- Model accuracy of 97.1% on test data
- Detailed prediction analysis showing predicted vs actual classes
- Model serialization using pickle for easy reuse

## Requirements
- Python 3.x
- Libraries:
  - numpy
  - pandas
  - scikit-learn
  - pickle

## Usage
1. Clone the repository
2. Install required libraries: `pip install numpy pandas scikit-learn`
3. Run the Jupyter notebook `Car evaluation.ipynb`

## Results
The model achieves 97.1% accuracy on the test set, demonstrating excellent performance in classifying car acceptability based on the given features. The notebook includes detailed output showing predictions and actual values for each test case.
