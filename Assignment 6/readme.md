## Assignment 06
You'll be creating a model that takes in a sentence and predicts the appropriate emoji that describes the sentiment (similar to the IMDB example we did this week but with extra sentiments (6 instead of just 2)).
### DATASETS:
The dataset consists of two csv files, a training file with 16k rows and a testing file with 2k rows, each row has 3 columns, the sentence, the emotion as text (meant to provide description to the emoji and not to be used in training/testing) and the emoji symbol (e.g. 😄, 😡, 😍).
The dataset is available here: https://drive.google.com/.../1i7LmIH7sJHSARAMXgznBqXZ82tz...
### REQUIREMENTS:
-Set TensorFlow's random seed to 42

-Read data from CSV files and split it into inputs and targets (no need to do train_test_split as the data is already split).

-Tokenize and pad the text, use a vocabulary size of 10,000 and maximum sequence length of 64.

-Do the appropriate operations on the targets to prepare them for training.

-Define the sequential model, make sure to use LSTM and Embedding layers.

-Use Adam optimiser and the appropriate loss function and metrics to compile the model.

-Use ModelCheckpoint callback to save the model at the epoch with the best validation accuracy, the model file should have your name (e.g. for Sabri Monaf, the model's file name would be "sabri_m.h5). Make sure to download the model file as it will be a part of your assignment submission. (the documentation for ModelCheckpoint can be found here: https://www.tensorflow.org/.../callbacks/ModelCheckpoint).

-The training and validation accuracy should be at least 90% and 85% respectively.

-Create a cell in the end that takes in an input string (inputted using Colab Forms (see details here: https://colab.research.google.com/notebooks/forms.ipynb) and uses the trained model to predict (make sure to convert the vector output to the appropriate emoji and print only the emoji at the end of the cell).
