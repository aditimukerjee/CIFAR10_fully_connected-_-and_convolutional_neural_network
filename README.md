# CIFAR10_fully_connected-_-and_convolutional_neural_network
Here I explored the CIFAR10 dataset using the fully connected and convolutional neural network.

I employed vaious techniques to increase accuracy, reduce loss, and to avoid overfitting.

Three callbacks have been defined to pevent overfitting and for better tuning of the model.

For fully connected model we get the following metrics on testing the model:
- Categorical cross-entropy: 1.2
- Accuracy: 58%
- The size of the wrongly classified iamges is 4215

For convolutional neural network model we get the following metrics on testing the model:
- Categorical cross-entropy: 0.39
- Accuracy: 89%
- The size of the wrongly classified iamges is 1108
