# Building My Recurrent Neural Network - Step by Step

This repository contains the programming assignment from **Week 1** of **Course 5: Sequence Models** in the [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) by Andrew Ng on Coursera.

## Overview

In this assignment, a Recurrent Neural Network (RNN) is implemented from scratch using NumPy. The objective is to gain a deep understanding of how RNNs process sequences over time and how gradients are computed through backpropagation through time (BPTT).

The RNN is applied to a character-level language model, which is trained to generate new names based on a dataset of examples.

Key topics covered in this assignment:
- One-hot encoding of input sequences
- RNN forward propagation
- RNN backward propagation
- Gradient clipping to handle exploding gradients
- Sampling and sequence generation
- Parameter optimization and updates

## Contents

- `rnn_utils.py` – Contains helper functions for data preprocessing and initialization
- `rnn_forward()` – Computes forward propagation through the RNN
- `rnn_backward()` – Computes the backward pass using BPTT
- `clip()` – Implements gradient clipping
- `sample()` – Generates new text sequences from trained parameters
- `optimize()` – Runs one step of forward-backward propagation and updates parameters
- `model()` – Trains the RNN on the full dataset

## Technologies Used

- Python 3
- NumPy

No external deep learning libraries (e.g., TensorFlow or PyTorch) are used in this assignment.

## Course Information

- Course: Sequence Models (Course 5 of 5)
- Specialization: Deep Learning Specialization
- Instructor: Andrew Ng
- Platform: Coursera
- Institution: DeepLearning.AI

## License

This repository is based on educational content provided by DeepLearning.AI through Coursera. It is intended for personal and academic use only. Redistribution for commercial purposes is not permitted.
