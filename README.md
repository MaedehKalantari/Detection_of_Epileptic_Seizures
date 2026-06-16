# Detection of Epileptic Seizures Using EEG Signals and CNN

## Overview

This project focuses on the automatic detection and classification of epileptic conditions using **electroencephalography (EEG)** signals. A deep learning approach based on a Convolutional Neural Network (CNN) is developed to classify individuals into three categories:

* Healthy subjects
* Patients experiencing epileptic seizures
* Patients with non-seizure epileptic activity

The goal is to support early and accurate diagnosis of epilepsy using data-driven methods.

---

## Dataset

The EEG dataset used in this project is provided by the **University of Bonn, Epileptologie Neurophysiology Group**:

[UK Bonn EEG Dataset](https://www.ukbonn.de/epileptologie/arbeitsgruppen/ag-lehnertz-neurophysik/downloads/?utm_source=chatgpt.com)

This dataset is widely used in epilepsy research and contains labeled EEG recordings from different patient groups.

---

## Methodology

### 1. Data Preparation

* EEG signals were preprocessed for noise reduction and normalization
* Signals were structured into segments suitable for CNN input
* Data were split into training and testing sets

### 2. Model Architecture

A Convolutional Neural Network (CNN) was designed with the following structure:

* Two convolutional layers
* Max-pooling layers after each convolution
* Fully connected (dense) layers
* Softmax output layer for multi-class classification

### 3. Training Process

* Loss Function: Cross-Entropy Loss
* Optimizer: Stochastic Gradient Descent (SGD)
* Training was performed over multiple epochs to improve model performance

---

## Evaluation

The trained model was evaluated on a separate test dataset and achieved:

* **Accuracy: 97.78%**

This demonstrates strong performance in distinguishing between healthy, seizure, and non-seizure EEG patterns.

---

## Results Summary

The CNN model successfully learned discriminative features from EEG signals and provided high classification accuracy, showing its potential for assisting in epilepsy diagnosis.

---

## Technologies Used

* Python
* NumPy / Pandas
* PyTorch or TensorFlow (depending on implementation)
* Matplotlib / Seaborn
* Scikit-learn

---

## Project Goal

The main objective is to explore how deep learning models can assist in medical signal interpretation and improve automated diagnosis of neurological disorders such as epilepsy.

---

