# GenZDealZ.ai-user-purchase-prediction
# Purchase Sequence Prediction

This project aims to predict the next user purchase based on a sequence of past transactions using a combination of LSTM and SimpleRNN layers in a neural network. The model processes encoded purchase sequences and predicts future buying behavior, leveraging a synthetic dataset of 47 e-commerce platforms.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)

## Project Overview
The project utilizes a deep learning approach to predict the next item a user will purchase based on their previous purchase history. It involves creating a synthetic dataset, encoding purchase sequences, and training a model using TensorFlow.

## Dataset
The dataset consists of synthetic user purchase sequences from 47 different e-commerce platforms. Each entry includes a user ID and a list of purchases.

## Model Architecture
The model uses:
- An LSTM layer to capture long-term dependencies in the purchase sequences.
- A SimpleRNN layer to capture simpler temporal dependencies.
- A Dense layer with softmax activation for predicting the next purchase.

## Setup Instructions
Follow these steps to set up and run the project:


python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
python main.py
