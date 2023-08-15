# Calculating-Categorical-Loss
Calculating loss with categorical cross entropy

- Categorical Cross-Entropy (CCE)    
    Is a commonly used loss function in neural networks and classification tasks with multiple classes  
    Is used to used to measure the difference bwteen predictied class probabilites and actual target class probabilities

- How It Works
      - Predicted Probabilites: Is a classification problem, the neural network predicts the probabilites of each class for a given input. They are calculated using the softmax activation function ensuring that they have the sum of 1    
      - Target Class Proababilites: Creating a one hot encoded vector where the true label (input sample) is assigned a probabiltiy of 1 and all the other classes a probability of 0
      - Loss Calculation: Categorical Cross-Entropy calculates the difference between the predicted probabilities and the target class proabbabilties for each sample  
      - Total Loss:  The total loss in the datatset is then averaged to obtain the overall loss of the entire dataset. This is what you optimize during the training of the model to update its parameters
      - Backpropagation & Optimization:
              > BackPropagation: The graident of the loss with respect to the the models parameters are calculated. These gradients are used to adjust the parameters through optimization like Gradient Descent. The goal is to minimize the loss improving the models predictions  
  
  
