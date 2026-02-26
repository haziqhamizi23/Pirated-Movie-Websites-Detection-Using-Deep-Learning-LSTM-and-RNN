Overview

This project focuses on detecting pirated websites using machine learning and deep learning techniques. It implements a complete preprocessing pipeline, feature extraction system, and classification models using Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM).

The system extracts 28 URL-based features and uses them to classify websites into:

0 — Benign website

1 — Pirated website



Machine Learning Models

Two deep learning models are implemented and compared:

1. Recurrent Neural Network (RNN)

Architecture:

SimpleRNN layer (64 units)

Dropout layer (0.3)

Dense output layer (Sigmoid)

2. Long Short-Term Memory (LSTM)

Architecture:

LSTM layer (64 units)

Dropout layer (0.3)

Dense output layer (Sigmoid)
