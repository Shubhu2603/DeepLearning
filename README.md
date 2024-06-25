# Breast Cancer Prediction using MP Neurons and Perceptron

## Overview
This project aims to predict breast cancer using machine learning models such as MP Neurons and Perceptron. The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) Data Set, which contains features computed from digitized images of breast cancer biopsies. The goal is to classify tumors into malignant (cancerous) or benign (non-cancerous) based on these features.

## Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set, which is available on the UCI Machine Learning Repository [here](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)). The dataset contains the following features:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave points
- Symmetry
- Fractal dimension

The target variable is the diagnosis, which can be either "M" (Malignant) or "B" (Benign).

## Models Used
- **MP Neurons**: MP Neurons are the simplest form of artificial neurons, inspired by the behavior of real neurons. They classify inputs based on a threshold. In this project, MP Neurons are used to predict breast cancer based on the dataset features.
- **Perceptron**: The Perceptron is a type of artificial neuron that can make binary decisions. It takes multiple inputs, each with an associated weight, and produces a single binary output. In this project, a Perceptron is trained to classify breast cancer based on the dataset features.
