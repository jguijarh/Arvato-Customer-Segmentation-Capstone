# Arvato Customer Segmentation Capstone
## Arvato Customer Segmentation Capstone overview
This repository contains the information corresponding to the project developed as Capstone Project for Machine Learning Engineer Nanodegree of the Udacity platform.

In this project the analysis of the data provided by Udacity and Arvato is performed, as well as the implementation of unsupervised models to develop population segmentation in the data and finally the development of supervised models to predict future company campaigns and make them more efficient.

## Installation

This project is built on Python 3.7 and all the necessary modules to run this project are collected in the `requirements.txt` file.

## Data files

The information to be used in this project is that provided by Udacity and Arvato for the project.There are four data files associated with this project:

- `Udacity AZDIAS 052018.csv`.
- `Udacity CUSTOMERS 052018.csv`.
- `Udacity MAILOUT 052018 TRAIN.csv`.
- `Udacity MAILOUT 052018 TEST.csv`.


## Support files
Some of the functions used inside the files are developed inside the file `helpers_data_cleaning.py`

## Instructions
To make use of the project, you must access to the repository notebooks and execute the commands presented in it. This project uses two notebooks, which must be executed in the order indicated:
- 1_Preprocessing_and_unsupervised_algorithms : includes data preprocessing and Unsupervised learning techniques
- 2_ML_algorithms_for_supervised_learning : supervised learning models and metrics evaluation.

## Analysis process inside the project
### Data cleaning and preprocessing
In this first section an initial display of the relevant data and metrics is carried out as well as their cleaning for further steps.
### Population segmentation with unsupervised leraning
Using a PCA model, the simplification of variables within the data set is carried out. Then, a Kmeans model performs unsupervised learning for the detection of sets within the population.
### Mailout campaigns forecasting with supervised models
Implementation of supervised models such as XGBoost, Catboost or LGBM for the forecasting of future company campaigns seeking to improve their performance, testing different types of data with which to train the models used.

## Results
After the whole process performed in this project, the forecast of a dataset associated to a competition within Kaggle is carried out, in which thanks to the model parameterized in this project, the second position has been obtained (with an AUC of 0.80954), so I think this project has a very good performance and has satisfied the expectations that were at first.


## Authors

* **Julio Guijarro**  - [Julio Guijarro](https://github.com/jguijarh)

## License

This project is licensed under the MIT License.
