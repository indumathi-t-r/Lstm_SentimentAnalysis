# Sentiment Analysis using Deep Learning (PyTorch)

This repository contains a sentiment analysis project implemented using **PyTorch**, focusing on classifying text data into sentiment categories such as positive, negative, and neutral. The notebook demonstrates a complete NLP pipeline starting from raw text preprocessing to training and evaluating deep learning models for sentiment prediction.

## Project Structure
The project is organized in a simple, notebook-centric structure:
- A single Jupyter Notebook that contains data loading, preprocessing, model definition, training, and evaluation.
- All experimentation, analysis, and visualization are performed within the notebook itself.
- The dataset is read directly within the script and processed step by step for modeling.

## What’s happening in the script
- Raw text data is cleaned and preprocessed (tokenization, vocabulary creation, and sequence padding).
- Text is converted into numerical representations suitable for neural networks.
- An embedding layer is used to learn word representations.
- A deep learning model (such as LSTM/GRU/CNN as implemented in the notebook) is trained to capture contextual information from text sequences.
- The model is optimized using a loss function and optimizer defined in PyTorch.
- Model performance is evaluated using accuracy and loss metrics, with basic visualizations where applicable.

## Script contains
- Text preprocessing and vocabulary construction
- Tokenization and sequence padding
- Embedding layer setup
- Deep learning–based sentiment classification model
- Training and validation loops
- Model evaluation and result analysis

## Requirements
Python 3.9+

## Main libraries used:
- numpy
- pandas
- matplotlib
- scikit-learn
- torch
- nltk (or equivalent tokenizer used in the notebook)
