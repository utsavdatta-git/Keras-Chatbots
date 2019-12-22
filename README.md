# keras_chatbots
  
Chatbots (Chat-oriented Conversational Agent) are designed to handle full conversations, mimicking the unstructured flow of a human to human conversation. In this project, I have tried to implement a basic (chit-chat) chatbot using Sequence to Sequence (seq2seq) model and Word Embeddings (Glove). First, I have created a baseline model using a Sequential keras model with a bi-directional LSTM layer. Then, I improved on it using a seq2seq model architecture and fastText word embeddings.
Additionally, the chatbot created using seq2seq model is personality driven (Professional, Friendly and Comic) and the user can choose to change the personality of the chatbot anytime during the conversation.

# Datasets

https://github.com/Microsoft/BotBuilder-PersonalityChat/tree/master/CSharp/Datasets (for model training)
https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html (for fastText word embedding training)

# Training

Running the notebook sequentially will take care of the preprocessing, training and testing (at the end).

# Pre-trainied models

Alternatively, pre-trained models of the seq2seq architecture are also provided.
