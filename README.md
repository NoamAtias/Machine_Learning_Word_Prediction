# Deep Learning Homework 2: Word Prediction

Welcome to the repository for Homework 2 in the Deep Learning course. In this assignment, our goal is to build a neural network that can predict the next word in a sentence based on the previous three words. By training this prediction model, we will explore word representations and analyze the vector representations learned by our model.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Word Representations](#word-representations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this assignment, we aim to develop a neural network that can accurately predict the next word in a sentence. By training the model on a given dataset, we explore the power of deep learning in understanding word relationships and generating coherent text.

## Dataset

The dataset for this assignment will be provided to you separately. It consists of a collection of sentences, where each sentence is split into words. The task is to train the model to predict the next word in a sentence based on the previous three words.

## Model Architecture

Our neural network model will be designed using deep learning techniques. The specific architecture will be explained in detail in the code files provided. The model will take the three previous words as input and output the predicted next word. The architecture may include recurrent neural networks (RNNs) or transformer-based models to capture the contextual information and dependencies between words.

## Training

To train the word prediction model, we will use the provided dataset. The training process involves feeding the input sequences (three previous words) to the model and optimizing the model parameters using backpropagation and gradient descent algorithms. The specifics of the training process will be explained in the code files provided.

## Evaluation

We will evaluate the performance of our trained word prediction model using appropriate evaluation metrics such as accuracy or perplexity. These metrics will help us assess the model's ability to generate accurate predictions and capture the underlying language patterns.

## Word Representations

As part of this assignment, we will explore the vector representations learned by our model. These representations encode the semantic and syntactic information of words and can provide insights into how the model understands and represents words in the given context. We will analyze and visualize these representations to gain a better understanding of our model's internal workings.

## Usage

To use the code and replicate the results of this homework, follow these steps:

1. Clone the repository: `git clone https://github.com/NoamAtias/Machine_Learning_Word_Prediction.git`
2. Navigate to the project directory: `cd Machine_Learning_Word_Prediction`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the training script: `python train.py`
5. Evaluate the model: `python evaluate.py`
6. Analyze word representations: `python analyze_representations.py`

Please note that the exact commands and file names may vary depending on the specific implementation.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
