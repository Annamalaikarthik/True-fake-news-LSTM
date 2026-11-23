# True Fake News LSTM

This repository contains a Long Short-Term Memory (LSTM) neural network model designed to classify news articles as true or fake.

## Project Overview

The goal of this project is to utilize deep learning techniques, specifically Recurrent Neural Networks (RNNs) with LSTM units, to detect misinformation in news articles.

## Dataset

The model is trained on a dataset of news articles, labeled as either `True` or `Fake`. 

*   **Source:** [Link to Dataset]
*   **Features:** Title, Text, Subject, Date

## Model Architecture

The LSTM model consists of the following layers:
*   **Embedding Layer:** Converts words into dense vectors of fixed size.
*   **LSTM Layer:** Captures the sequential nature of the text.
*   **Dense Layer:** Outputs the final classification (True/False).

## Installation

To run this project, install the required dependencies:

```bash
pip install -r requirements.txt
