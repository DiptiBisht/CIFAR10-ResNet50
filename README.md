# CIFAR10-ResNet50

CIFAR-10 (https://en.wikipedia.org/wiki/CIFAR-10Links to an external site.) is a challenging image recognition problem. Performance of this particular CNN model we did in class is not very good: CIFAR10_TransferLearning_Xception.ipynbDownload CIFAR10_TransferLearning_Xception.ipynb

In this team assignment, modify the given CNN model to achieve an accuracy of at least 85% on the test data. You should try the following to get a better accuracy:

1. Experiment with the CNN model

You can retrain some of the top layers of the Xception model that was used for transfer learning. In Python Tutorial 7, we retrained about top 5 layers. You can retrain more top layers to get better accuracy.

2. Experiment with the multi-layer fully connected feed forward NN after the CNN layers:

Convolutional networks work by convolving over images, creating a new representation, and then compressing this representation into a vector that is fed into a classic multilayer feed-forward neural network. You can try adding more hidden layers or altering the number of neurons in each of these hidden layers in the fully connected layers.

3. Experiment with the Dropout rates:

You can use Dropouts at almost every convolutional and fully-connected layers. Try using different Dropout rates in different layers to get a better overall accuracy.
