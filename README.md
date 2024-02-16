# Credit Card Fraud Detection using Neural Networks

This project demonstrates how to build a neural network for detecting fraudulent credit card transactions. The dataset used for this project contains anonymized data about credit card transactions, including over 285,000 transactions made by European cardholders in September 2013. This project utilizes deep learning techniques to classify transactions as legitimate or fraudulent based on the available features.

# Project Overview

Credit card companies use machine learning models to detect fraud in real-time. In this project, we use a dataset published on Kaggle to demonstrate how to apply a simple neural network model to fraud detection. Although the features in the dataset are anonymized using techniques like Principal Component Analysis (PCA), the dataset still provides an opportunity to develop and train models that effectively classify fraudulent and non-fraudulent transactions.

# Dataset

The dataset contains the following:

- Number of transactions: 285,000+
- Number of fraudulent transactions: 492
- Number of legitimate transactions: 284,315
- Features: 30 (V1-V28 from PCA, Time, and Amount)
- Target variable: Class (1 for fraudulent transactions, 0 for legitimate transactions)

***Files in the Repository***

- Fraud Dection.py: The main script that loads the dataset, builds the CNN model, trains it, and evaluates performance.
- README.md: Provides an overview of the project and instructions on how to run it.

***Dataset***
The dataset used is structured as follows:

Data/
├── Creditcard.csv/

- Time: The time difference between this transaction and the first transaction in the dataset.
- V1 to V28: Anonymized features obtained via Principal Component Analysis (PCA).
- Amount: The transaction amount.
- Class: The label indicating whether the transaction is fraudulent (1) or legitimate (0).

# Model

We use a simple neural network with two fully connected layers:

- Input Layer: 128 neurons with ReLU activation
- Output Layer: 1 neuron with sigmoid activation (binary classification)



***Requirements***

To run this project, you will need:

- Python 3.7+
- TensorFlow / Keras
- NumPy
- Matplotlib
- OS Library for handling file paths

# To install the dependencies, run:
pip install tensorflow numpy matplotlib

# How to Run

***Clone the repository:***
- https://github.com/Tejasreebussa/Fraud-Dection
- cd IFraud-Dection

***Run the script:***
python Fraud Dection.py

Ensure the dataset is placed in the correct directory (Data/).