# 🧠 Predicting Next Word in a Sentence using GRU RNN

This project demonstrates a **Next Word Prediction** application built using a **Gated Recurrent Unit (GRU)** model. The model is trained on a text dataset to predict the next word given a sequence of input words. The web application is built using **Streamlit** to provide an interactive interface for users to enter text and get real-time word predictions.

## 🚀 Streamlit Web Application

The project includes a user-friendly web application where users can input a sequence of words and predict the next word using the GRU-based model.

<p align="center">
  <a href="https://your-streamlit-app-link">
    <img src="https://streamlit.io/images/brand/streamlit-logo-secondary-colormark-darktext.png" width="250" alt="Streamlit Logo">
  </a>
</p>

### Key Features:
- **GRU-based model** for next-word prediction in a text sequence.
- **Interactive UI** built with Streamlit for real-time predictions.
- **Tokenizer** for converting input text into sequences, ensuring compatibility with the model.

## 📂 Project Structure



## 🔍 Model Details

The model used in this project is a **Gated Recurrent Unit (GRU)**, a type of RNN that is particularly good at capturing long-term dependencies in sequences. The key steps in the model training are as follows:

- **Tokenizer**: Tokenizes the input text to convert it into numerical sequences.
- **Padding**: Pads the input sequences to ensure they are all the same length.
- **GRU Layer**: A recurrent neural network layer to learn the sequence patterns.
- **Dense Layer**: Outputs the probability distribution over the vocabulary for the next word prediction.

## 📝 Preprocessing

The preprocessing steps for the input text are:
1. **Tokenization**: Convert the input words into a sequence of integers using the pre-trained tokenizer.
2. **Padding**: Apply padding to make the input sequence the same length as required by the GRU model.

## 💻 Usage

### Running the App Locally

To run the Streamlit app locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Next_Word_Prediction.git
    cd Next_Word_Prediction
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the app**:
    ```bash
    streamlit run app.py
    ```


## 🔗 Links
- **Streamlit**: [https://streamlit.io/](https://streamlit.io/)
- **TensorFlow/Keras**: [https://www.tensorflow.org/](https://www.tensorflow.org/)
