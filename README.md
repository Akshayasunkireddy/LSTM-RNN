# LSTM-RNN: Next Word Prediction

A simple NLP app that predicts the next word in a sentence using an LSTM (Long Short-Term Memory) neural network. Built with TensorFlow/Keras and deployed using Streamlit.


## Demo

> Example Input:  
> `"To be or not to"`  
> **Prediction:** `live` (example)

## Model Details

- **Model**: LSTM (Sequential Keras model)
- **Framework**: TensorFlow / Keras
- **Trained On**: Text corpus tokenized and padded
- **Tokenizer**: Stored as `tokenizer.pickle`
- **Output**: Most probable next word using `argmax` on softmax layer

## Project Structure

├── app.py # Streamlit app
├── next_word_lstm.h5 # Trained LSTM model
├── tokenizer.pickle # Tokenizer used for training
└── README.md # Project overview


## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Akshayasunkireddy/LSTM-RNN.git
cd LSTM-RNN

# Install dependencies:
pip install -r requirements.txt

#Run the Streamlit app:
streamlit run app.py

## Requirements

streamlit
tensorflow
numpy

## Author

Akshaya Sunkireddy
🔗 GitHub: https://github.com/Akshayasunkireddy




