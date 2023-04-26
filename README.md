# LSTM_Chatbot
This project involves building an LSTM-based chatbot using Python and TensorFlow. 
The chatbot is trained on a JSON file that contains a list of intents and their corresponding inputs and tags. 
The inputs and tags are loaded into two separate lists, which are then used to create a Pandas DataFrame. 
The inputs are preprocessed by removing punctuation and converting all text to lowercase. 
The input data is tokenized using the Keras Tokenizer, and the output data is encoded using the LabelEncoder from Scikit-learn. 
The LSTM model is built using Keras, with an embedding layer, an LSTM layer, and a dense output layer with a softmax activation. 
The model is trained for 200 epochs, and the resulting chatbot can respond to user input by predicting the appropriate response based on the input's tag. 
The chatbot's performance can be further improved by fine-tuning the model or increasing the amount of training data.


**Things to do:** To make chatbot more effective, train the chatbot using more data.
