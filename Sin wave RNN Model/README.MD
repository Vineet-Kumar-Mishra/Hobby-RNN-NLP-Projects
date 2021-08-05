## This is a simple RNN model to work on deterministic series data

### 1. The data of sin(wt) has been generated and w = 0.1 and t = 0 to 1000
### 2. T = 10 here and D = 1 i.e. each input series is of length 10 and dimension 1
### 3. The functional API of keras is used with simpleRNN having 20 neurons with default tanh activation
### 4. The mse is selected as loss
### 5. The results are appreciable since sin(wt) is deterministic signal hence the predicted label and correct labels are very close to each other
