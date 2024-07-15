# WizWord Generator

WizWord Generator is a next-word prediction model based on LSTM (Long Short-Term Memory) Recurrent Neural Networks. This project predicts the next word in a sequence of text, specifically trained on dialogues extracted from the "Harry Potter" series.

## Introduction

WizWord Generator utilizes deep learning techniques, specifically LSTM RNN architecture, to predict the most probable next word in a sentence or dialogue. The model learns from a dataset consisting of conversations and dialogues from the beloved "Harry Potter" books, allowing it to generate contextually relevant predictions within that fictional universe.

## Architecture

The architecture of WizWord Generator revolves around LSTM (Long Short-Term Memory) Recurrent Neural Networks:

- **LSTM RNN**: LSTM networks are well-suited for sequence prediction tasks due to their ability to capture long-term dependencies in data. They maintain an internal state (cell state) that can remember information for long periods, making them ideal for understanding and predicting sequences of words.

- **Tokenization and Padding**: Input sequences are tokenized into numerical indices and padded to a fixed length using TensorFlow's Keras `pad_sequences` function. This preprocessing step ensures that all input sequences have the same length, essential for efficient batch processing during training.

- **Training**: The model is trained on a dataset prepared from the "Harry Potter" series dialogues. During training, the LSTM network learns to predict the next word in a sequence based on the context provided by preceding words.


