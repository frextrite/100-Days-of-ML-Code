# MNIST Classifier Deep
MNIST classifier using a Deep Neural Network, having 2 hidden layers, each having 512 nodes. This model gives an accuracy of 96.08%, 5.32% higher than the previous model.

Link to tutorial: https://www.tensorflow.org/versions/r1.2/get_started/mnist/beginners

Found a great article comparing accuracies of different MNIST Classifier models: https://www.cse.iitk.ac.in/users/khalidi/Docs/mnist.pdf

Things to note about tensorflow:
  - Always use tf.random_normal() instead of tf.zeros() to initialize weights and biases
  - GradientDescentOptimizer is slow to converge, use AdamOptimizer instead

Update(July 12, 2018): Fixed code to use SGD correctly. Accuracy bumped up to 97.88%

