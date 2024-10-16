# Vocabulary for Learning Representations by Backpropagating Errors

### 1. Neural Network (NN)

A computational model composed of layers of neurons, where each neuron performs a weighted sum of inputs followed by an activation function. Neural networks are used to model complex patterns and relationships in data.

### 2. Backpropagation

A supervised learning algorithm used to calculate the gradient of the loss function with respect to each weight by propagating the error backwards from the output layer to the input layer.

### 3. Activation Function

A function applied to the output of each neuron to introduce non-linearity, allowing the network to learn complex patterns. Common examples include **sigmoid**, **ReLU**, and **tanh**.

### 4. Sigmoid Function

A type of activation function defined as:
σ(x) = 1 / (1 + exp(-x))
It squashes input values to the range (0, 1), making it useful for binary classification.

### 5. Loss Function

A function that measures the difference between the predicted output and the true label. In this paper, the **mean squared error (MSE)** or **cross-entropy** can be used for optimization.

### 6. Gradient Descent

An optimization algorithm used to update the weights of the network by minimizing the loss function. It iteratively adjusts weights in the opposite direction of the gradient.

### 7. Weights and Biases

- **Weights:** Values that determine the importance of each input in the neuron’s computation.
- **Bias:** An additional term added to the weighted sum to shift the activation function's output.

### 8. Learning Rate

A hyperparameter that controls the size of the steps taken during gradient descent. A higher learning rate results in faster updates, but too high of a value can prevent convergence.

### 9. Epoch

One complete pass through the entire training dataset. Multiple epochs are used to iteratively improve the network’s performance.

### 10. Forward Pass

The process of passing input data through the network, layer by layer, to produce an output.

### 11. Chain Rule

A rule from calculus used to calculate the derivative of a composite function. It is essential for computing gradients in backpropagation.

### 12. Overfitting

When the model performs well on training data but fails to generalize to unseen data (test data). Regularization techniques can help mitigate overfitting.

### 13. Generalization

The ability of a neural network to perform well on new, unseen data, not just on the training data.

### 14. Supervised Learning

A type of learning where the model is trained on labeled data, meaning each input has a corresponding output (label).

### 15. Mini-batch Gradient Descent

A variation of gradient descent where the dataset is divided into small batches, and gradients are computed for each batch. This can speed up training and improve convergence.
