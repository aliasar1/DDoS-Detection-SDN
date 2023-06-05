# DDOS Attack Detection using SDN Network

This repository contains the implementation of a DDOS attack detection system using a Software-Defined Networking (SDN) network. The system employs various machine learning algorithms to classify network traffic data and identify potential DDOS attacks. The implemented algorithms include Gaussian Naive Bayes (GNB), Logistic Regression (LR), Decision Tree (DT), Artificial Neural Network (ANN), Long Short-Term Memory (LSTM), Ensemble Classifier (GBC), and Support Vector Classifier (SVC).

## Table of Contents
- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Algorithms](#machine-learning-algorithms)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
DDOS (Distributed Denial of Service) attacks are a serious threat to network infrastructure and can cause severe disruptions. This project aims to develop a system that can detect and mitigate such attacks using SDN technology. The SDN network provides better control and visibility of network traffic, enabling efficient detection and response to anomalies.

The implemented system follows a machine learning-based approach to identify DDOS attacks. The network traffic data is preprocessed using Exploratory Data Analysis (EDA) techniques and then transformed using one-hot encoding to prepare it for the machine learning algorithms. Various classifiers, including GNB, LR, DT, ANN, LSTM, GBC, and SVC, are trained on the preprocessed data to classify network traffic into normal or attack categories.

## Data Preprocessing
Before training the machine learning algorithms, the network traffic data undergoes a preprocessing stage. The following steps are performed as part of the data preprocessing:

1. **Exploratory Data Analysis (EDA):** This step involves analyzing the data to gain insights into its characteristics. EDA techniques are applied to understand the distribution of features, identify missing values, outliers, and correlations between variables.

2. **One-Hot Encoding:** Categorical variables in the data are encoded using one-hot encoding. This process converts categorical features into binary vectors, enabling machine learning algorithms to process them effectively.

## Machine Learning Algorithms
The system utilizes various machine learning algorithms to classify network traffic and detect potential DDOS attacks. The implemented algorithms are as follows:

1. **Gaussian Naive Bayes (GNB):** GNB is a probabilistic algorithm that applies Bayes' theorem with the assumption of independence between features. It is efficient for classification tasks with discrete features.

2. **Logistic Regression (LR):** LR is a linear classification algorithm that models the probability of the input belonging to a particular class. It is widely used for binary classification problems.

3. **Decision Tree (DT):** DT is a tree-based algorithm that makes decisions based on a sequence of rules. It splits the data based on features to create a tree-like model for classification.

4. **Artificial Neural Network (ANN):** ANN is a deep learning algorithm inspired by the human brain's neural structure. It consists of multiple layers of interconnected nodes (neurons) and is effective for complex classification tasks.

5. **Long Short-Term Memory (LSTM):** LSTM is a type of recurrent neural network (RNN) that can capture dependencies and patterns in sequential data. It is suitable for analyzing time-series data, such as network traffic.

6. **Ensemble Classifier (GBC):** Gradient Boosting Classifier (GBC) is an ensemble learning method that combines multiple weak classifiers to create a strong classifier. It builds a sequence of models, where each model corrects the mistakes of the previous ones.

7. **Support Vector Classifier (SVC):** SVC is a supervised learning algorithm that builds

 a hyperplane or set of hyperplanes to separate data into different classes. It can handle complex, high-dimensional data and is effective in binary and multiclass classification problems.

## Installation
To use this repository, follow these steps:

1. Clone the repository using the following command:
   ```
   git clone https://github.com/aliasar1/DDoS-Detection-SDN.git
   ```

## Usage
1. Prepare your network traffic data in a suitable format. Ensure that the data contains the necessary features required for training the machine learning algorithms.

2. Preprocess the data using EDA techniques and one-hot encoding. You can refer to the provided code files for guidance on how to preprocess the data.

3. Train the machine learning algorithms using the preprocessed data. Use the respective algorithm's implementation to train and evaluate the models.

4. Test the trained models on new network traffic data to detect potential DDOS attacks. You can use the trained models to classify incoming network traffic and identify any suspicious patterns.

## Contributing
Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. 

When contributing, please ensure to follow the existing code style and conventions. Also, provide clear descriptions and explanations for your contributions.
