# Parkinson’s Disease Detection
This repository contains a Jupyter Notebook (Parkinson’s Disease Detection.ipynb) which demonstrates the detection of Parkinson's Disease using machine learning techniques, particularly Support Vector Machine (SVM) classification.

## Introduction
Parkinson's Disease is a neurodegenerative disorder that affects movement. Early detection and diagnosis are crucial for effective management of the disease. This notebook utilizes SVM, a supervised learning algorithm, to classify whether a patient has Parkinson's Disease based on certain features extracted from biomedical voice measurements.

## Prerequisites
- NumPy
- Pandas
- Scikit-learn

## Preprocessing
The data preprocessing steps include:
1. Loading the dataset using Pandas.
2. Exploring the dataset to understand its structure and characteristics.
3. Handling missing values (no missing values found in this dataset).
4. Normalizing the feature data using StandardScaler.
5. Model Training
6. The SVM model with a linear kernel is trained on the normalized data. The linear kernel is chosen due to the assumption of linear separability in the feature space. The model is trained using a portion of the dataset and evaluated on another portion to assess its performance.

## Evaluation
The performance of the trained model is evaluated using accuracy scores on both the training and testing datasets.

# Inference
A sample input data is provided to demonstrate how the trained model can be used for inference. The input data represents biomedical voice measurements of an individual. The model predicts whether the individual has Parkinson's Disease based on these measurements.

## Usage

- Clone the repository.
- Ensure you have Jupyter Notebook installed.
- Open the notebook (Parkinson’s Disease Detection.ipynb) in Jupyter Notebook.
- Execute the cells sequentially to reproduce the analysis.

## Refferences
- Naveen Kumar. (2021). Parkinson's Disease Detection Using ML Algorithms. [Dataset](https://www.kaggle.com/code/naveenkumar20bps1137/parkinson-s-disease-detection-using-ml-algorithms/input)
