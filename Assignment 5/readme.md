## Assignment 05/

You will use the Fashion MNIST dataset to build two deep learning models, one implemented as a Fully Connected Network (FCN/DNN), and one as a Convolutional Neural Network (CNN).

### DATASETS:

-The dataset is available at: `tf.keras.datasets.fashion_mnist.load_data()`

-and use `tf.data` to load the data into the fit method.

### REQUIREMENTS:

-Set the random seed for TensorFlow using `tf.random.set_seed(42)` to ensure having reproducible results.

-One Hot encode your targets/outputs.

-Set batch size to 32 using `tf.data` pipeline.

-Set the test set in the fit method using `validation_data=(x_test, y_test)`.

-Use accuracy metric in the compile function to display training/validation accuracy during training.

-Use the appropriate optimizer and loss function

-Achieve a training accuracy of at least 85% and validation accuracy of 80% using DNN, and ~100% training accuracy and above 95% validation accuracy in CNN.

-Plot the loss/validation loss value over the training epochs for both models.
