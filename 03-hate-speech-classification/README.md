# Hate Speech Classification

Supervised machine learning case study focused on classifying text messages as hate speech or non-hate speech.

## Objective

The project compares several supervised classification models and different feature subsets in order to identify the most effective configuration for hate speech detection.

## Methodology

* Exploratory data analysis
* Class distribution analysis
* Correlation analysis
* Feature importance analysis
* Multiple feature-selection strategies
* Hyperparameter optimisation with GridSearchCV
* Model comparison
* Confusion matrices
* Final model selection

## Models

* Random Forest Classifier
* Support Vector Machine
* Decision Tree Classifier

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

## Dataset

The dataset is not included in this repository because it contains sensitive text content and redistribution rights are not guaranteed.

The notebook expects a local `out.csv` file with the required preprocessed features and labels.

## Technologies

* Python
* pandas
* NumPy
* scikit-learn
* Matplotlib
* Seaborn
* tabulate

## Project Files

* `hate_speech_classification.ipynb`: complete analysis and model comparison.
* `out.csv`: input dataset.

## Academic Context

This project was originally developed as group coursework for the Machine Learning course of the MSc in Artificial Intelligence.

The portfolio version preserves the original methodology, analysis and conclusions. Changes are limited mainly to documentation, organisation, compatibility updates and code presentation.
