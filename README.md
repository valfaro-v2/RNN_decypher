# Decoding Encrypted Messages using Recurrent Neural Networks (RNNs)

In this notebook we demonstrate an approach to decode encrypted messages using a Recurrent Neural Network (RNN). Specifically, we'll explore how RNNs can be trained to learn the underlying patterns in encrypted text and decode messages without prior knowledge of the encryption being in place. Three different RNN models will be trained and compared: Simple RNN, GRU and LSTM.

## Motivation:
In cryptography, decoding encrypted messages traditionally involves techniques such as genetic algorithms or brute force methods. This notebook aims to showcase the capabilities of RNNs in decoding encrypted messages (provided sufficient training data is available). 

## Contents:
1. [Importing necessary libraries.](#libraries)
2. [Preprocessing the data](#preprocessing): Tokenizing characters, encoding text, and preparing training data.
3. [Building the RNN models](#buildingmodel): Designing the architecture of the different RNN models for sequence-to-sequence learning.
4. [Training the RNN models](#trainmodel): Compiling and fitting the models on the training data.
5. [Evaluating the models](#evaluatemodel): Assessing the performance of the trained models on test data.
6. [Decoding encrypted messages](#decode): Using the trained models to decode new encrypted messages.