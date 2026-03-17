# Service-Desk-Ticket-Classification-with-Deep-Learning

## Overview

This project builds a deep learning model to classify service desk tickets into predefined categories. The goal is to automate ticket routing and improve customer service efficiency.

## Dataset

The dataset consists of:

* Tokenized text data stored in `text.json`
* Vocabulary stored in `words.json`
* Labels stored in `labels.npy`

## Model Architecture

The model is a Convolutional Neural Network (CNN) composed of:

* Embedding layer
* 1D Convolution layer
* ReLU activation
* Global average pooling
* Fully connected layer

## Training

* Loss function: CrossEntropyLoss
* Optimizer: Adam
* Epochs: 3
* Batch size: 400

## Evaluation Metrics

* Accuracy
* Precision (per class)
* Recall (per class)


* Training loss per epoch
* Accuracy
* Precision per class
* Recall per class
