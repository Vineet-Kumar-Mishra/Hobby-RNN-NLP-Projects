# This is a spam classification model usign LSTM
### 1. The spam data is downloaded from kaggle and also available in repo. This file has encoding 'ISO-8859-1'
### 2. Text processing is done. The tokenizer object is created to convert distinct words into tokens (integer representation). This same tokenizer converts a sentence into sequence usign texts_to_sequences
### 3. padding has to be done to match the sequence lengths
### 4. The Model consists of Embedding layer which converts these tokens into usefull vector representation i.e. similar words have high cosine similarity and vice-versa.
### 5. The LSTM has 15 neurons and a GlabalMaxPooling1D is used.
### 6. This is a binary classification with ADAM as optimizer.
### 7. The training accuracy is 99.97% while the validation accuracy is 98.56 %
