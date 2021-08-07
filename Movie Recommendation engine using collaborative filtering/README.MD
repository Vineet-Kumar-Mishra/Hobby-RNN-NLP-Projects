# Movie recommendation system using Collaborative filtering
### 1. Collaborative filtering has been used to predict the rating using regression
### 2. MovieLens dataset has been used for the task
### 3. functional API of keras is necessary for the task since half of the model is parallel and later half is concatenated .
### 4. The Movie ID and User ID is converted into embeddings parallely and then flattened and joined.
### 5. On this joint feature vector we use 2 fully connected layers to do regression.
### 6. We run for 28 epochs and validation loss = 0.6431 while root mean square error  = 0.801 which is kind of good for collaborative filtering.
