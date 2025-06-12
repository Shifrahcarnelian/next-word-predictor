# next-word-predictor
Predict the next word in a sentence using an LSTM-based neural network built with Keras and NLTK.# 🧠 Next Word Prediction using LSTM

This project implements a **Next Word Prediction** model using **Recurrent Neural Networks (RNN)** with **LSTM** layers in **Keras**. It learns from a large text dataset to predict the most likely word that comes next in a sentence.

---

##  Features

- Trains on any large text file (e.g., dialogues, books, transcripts)
- Uses NLTK for tokenization and preprocessing
- One-hot encoding for input sequences
- LSTM model trained with categorical crossentropy
- Plots training accuracy and loss
- Saves the trained model and training history

---

##  Files

| File | Description |
|------|-------------|
| `next_word_prediction.ipynb` | Main notebook containing the code |
| `model.h5` *(optional)* | Trained Keras model |
| `history.p` *(optional)* | Training history object (for plotting) |
| `README.md` | Project documentation |

---

##  Dataset

You can train this model on any text data of your choice.

Examples:
- Cornell Movie Dialogues
- Books (e.g., downloaded from Project Gutenberg)
- Chat logs or other `.txt` files

To use:
1. Upload your text file into Colab or the `sample_data/` folder
2. Update the path in the notebook accordingly

---

##  Requirements

This project runs in **Google Colab**, but you can also run it locally with:

- Python 3.x
- TensorFlow / Keras
- NumPy
- NLTK
- Matplotlib

To install dependencies locally:
```bash
pip install tensorflow keras nltk matplotlib


