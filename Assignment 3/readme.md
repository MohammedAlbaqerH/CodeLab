## Assignment 03/

### DATASET:

-We will be using the wine quality dataset, it's built into Scikit Learn so you can call it from the datasets module `datasets.load_wine()`.

-You will build a model that takes in the different features of wine and outputs a quality score from 0 to 2 (discrete values, not continuous)

-This dataset doesn't require any preprocessing so you can focus on applying cross validation and tuning the hyper parameters.

### REQUIREMENTS:

-Set random_state to 42 for every operation that accepts it.

-To split into training/testing set, use StratifiedShuffleSplit with split size of 10. Don't forget to set the random state to 42.

-Define your preferred model/algorithm for this task. Don't forget to set the random state to 42.

-Calculate the accuracy score for each fold, this dataset has multiple target classes so precision and recall aren't relevant here.

-Display the score for each fold and then the mean of these scores.

-Keep tuning the hyper-parameters until you reach an accuracy of 95% or more.
