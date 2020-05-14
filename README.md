# Sentiment-classification
 IMDB Movie reviews sentiment classification
 
1. Import required libraries and the dataset
2. Visualise a sample of dataset
3. Data preprocessing
4. Sequential Model Building with Activation for each layer
5. Compile with binary CE loss and metric accuracy
6. Train Model with cross validation, with total time taken shown for 20 epochs
7. Visualise Loss and Accuracy history
8. Show Confusion Matrix for validation dataset

# Hyperparameter Experiments 

 1. Network Depth : 
   1 Hidden Layer of 64 units
   2 Hidden Layer of 64-32 units
2. Regularisations : 
   1. Dropout of ratio 0.25
   2. Dropout of ratio 0.25 with L2 regulariser with factor 1e-04
3. Activations :
   1. ReLU for every hidden layer
   2. Sigmoid for every hidden layer (sigmoid for final layer)
4. Batch Size :
   1. 64
   2. 256
5. Optimisers : 
   1. Adam with lr 1e-03
   2. SGD with lr 1e-02 and momentum 0.95
   
# Summarise the results mentioning which of the above combinations gives highest accuracy and which one the lowest, providing your understanding behind them
