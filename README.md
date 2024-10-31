# Iris Flower Classification

This project aims to classify iris flowers into three species (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`) based on their physical measurements. The dataset used is the famous Iris dataset, which consists of 150 samples with four features.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction

The Iris dataset is a well-known dataset in the field of machine learning and statistics. It contains data on iris flowers, which can be classified into three species based on the lengths and widths of their sepals and petals. This project demonstrates the use of different classification algorithms to predict the species of iris flowers.

## Dataset

The dataset is available as `IRIS.csv` and can be found in the repository. The dataset contains the following columns:

- **sepal_length**: Length of the sepal (cm)
- **sepal_width**: Width of the sepal (cm)
- **petal_length**: Length of the petal (cm)
- **petal_width**: Width of the petal (cm)
- **species**: Species of the iris flower

## Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species

## Installation

To run this project, you need to have Python installed along with the following libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn

**Usage**
Clone this repository:

git clone https://github.com/yourusername/your-repo-name.git
Navigate to the project directory:

cd your-repo-name
Open a Python environment (Jupyter Notebook, IDE, etc.) and run the code to load the dataset and train the models.

**Model Training**
The following classification algorithms were implemented:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
The models are trained using the features of the dataset, and their performance is evaluated using accuracy score metrics.

**Results**
The accuracy scores for each model are as follows:

Algorithm	Accuracy Score
Logistic Regression	97.3%
Decision Tree	91.9%
Random Forest	94.6%
Support Vector Machine	97.3%

**Conclusion**
This project demonstrates how to classify iris flowers using different machine learning algorithms. The models achieve high accuracy, with Logistic Regression and SVM providing the best performance. The project serves as a foundational example for beginners to understand classification tasks using Python and machine learning.
