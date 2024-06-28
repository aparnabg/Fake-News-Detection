# Fake-News-Detection

This repository contains a Long Short-Term Memory (LSTM) based model for detecting fake news. The model is trained to classify news articles as real or fake based on their textual content.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)

## Introduction

Fake news detection is an important task to ensure the credibility of information. This project leverages the power of LSTM networks, a type of Recurrent Neural Network (RNN), to effectively classify news articles as real or fake.

## Features

- Preprocessing of text data
- Implementation of an LSTM model
- Training and evaluation scripts
- Performance metrics 

## Dataset

The dataset used is Kaggle Fake News dataset.

**train.csv**: A full training dataset with the following attributes:
- `id`: Unique id for a news article
- `title`: The title of a news article
- `author`: Author of the news article
- `text`: The text of the article; could be incomplete
- `label`: A label that marks the article as potentially unreliable
  - `1`: Unreliable
  - `0`: Reliable

## Model Architecture

The LSTM model is designed to handle sequential data and capture temporal dependencies in the text. Key components of the model architecture include:

- Embedding layer
- LSTM layer
- Dense layers

Then added Dropout layers and compared accuracy.

- Dropout layers: Regularizes the model to prevent overfitting.


## Results

The LSTM model with dropout layers shows improved performance in detecting fake news. 
