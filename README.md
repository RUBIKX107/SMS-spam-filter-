# SMS-spam-filter-

## Overview
This project implements a machine learning model to classify SMS messages as spam or not spam using **PyTorch**, **pandas**, and **scikit-learn**. It serves as a practical introduction to natural language processing and neural networks.

## Key Features
- Data preprocessing using **pandas**.
- Text transformation from strings to numerical representations.
- Neural network model trained with **PyTorch** over 20 epochs.
- Classification of messages into spam (1) and non-spam (0).

## Project Structure
sms_spam_filter/
│
├── data/ # Directory for storing datasets
│ └── sms_data.csv # Sample SMS data file
│
├── notebooks/ # Jupyter notebooks for exploration
│ └── data_analysis.ipynb
│
├── src/ # Source code for the project
│ ├── data_preprocessing.py # Data loading and preprocessing functions
│ ├── model.py # Model architecture and training
│ └── predict.py # Prediction functions
│
├── requirements.txt # Python package dependencies
└── README.md # Project documentation

## Installation
1. Clone the repository:
   ```bash

