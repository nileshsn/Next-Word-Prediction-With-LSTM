# Next Word Prediction with LSTM

This project demonstrates a Next Word Prediction model using an LSTM (Long Short-Term Memory) neural network. The model is built using TensorFlow and Keras, and the web application is implemented using Streamlit. The app predicts the next word based on the given input sequence of words.

## Demo

Check out the live demo of the application: [Next Word Prediction App](https://next-word-prediction-with-lstm-6md5nr6g2jaffp2db2rrft.streamlit.app/)

## Project Overview

The LSTM model is trained on a text dataset to predict the next word in a sequence. This is a common task in natural language processing (NLP) with applications in text generation, autocomplete, and more. The model is designed to provide a probable next word based on the input text sequence.

## Features

- Predicts the next word in a sentence based on the input text sequence.
- Utilizes an LSTM model for sequential data processing and prediction.
- User-friendly interface powered by Streamlit.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**

```bash
git clone https://github.com/nileshsn/Next-Word-Prediction-With-LSTM.git
cd Next-Word-Prediction-With-LSTM
```
2. **Create a virtual environment**

```bash
python -m venv venv
```
3. **Activate the virtual environment**
- For Windows:
```bash
venv\Scripts\activate
```
-For macOS and Linux:
```bash
source venv/bin/activate
```
4.Install the required dependencies

```bash
pip install -r requirements.txt
```
5. **Run the Streamlit app**
```bash
streamlit run app.py
```

## Usage
1.Open the app in your web browser (usually at `http://localhost:8501` by default).
2.Enter a sequence of words in the input field.
3.Click the "Predict Next Word" button to see the predicted next word.

## Model Details
- The model architecture is based on an LSTM neural network, which is particularly effective for processing and predicting sequences.
- The model has been trained on a dataset to learn the context and relationship between words.
  
## Files and Directories
- app.py: The main Streamlit app file for running the web interface.
- next_word_lstm.h5: The pre-trained LSTM model file.
- tokenizer.pickle: Tokenizer file used to preprocess text data for model prediction.
- requirements.txt: Python dependencies required to run the app.
- 
## Troubleshooting
If you encounter any issues while running the app, ensure that all dependencies are installed correctly and that your environment matches the required versions listed in requirements.txt. Also, ensure that your next_word_lstm.h5 and tokenizer.pickle files are in the correct directory.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The project uses TensorFlow and Keras for deep learning.
- Streamlit is used for the web application interface.
