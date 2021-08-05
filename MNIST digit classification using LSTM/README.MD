# This is a LSTM model to classify 10 classes of MNIST
### 1. The MNIST can be directly downloaded from keras datasets and used as tuples of train and test sets
### 2. The tuple are in shape (N, 28,28) so we can consider it as (N, T, D) i.e. T = 28 (instances) and D = 28 (dimensions of series)
### 3. Functional API of keras is used and LSTM with 125 neurons is used. The actiavation is kept tanh (default). The dense layer has 10 neurons with softma activation.
### 4. The model is compiled with ADAM as optimizer, sparse categorical crossentropy as loss and accuracy as metrics
### 5. Model is trained for 12 epochs
### 6. The model gives 99.44% training accuracy and 98.92 % as testing accuracy
