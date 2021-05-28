# A tale of two models

Comparing two machine learning models to predict the survival rates of Titanic passengers.

The purpose of this exercise was to compare the selection of an algorithm beforehand - In this case the Naive Bayes - and the usage of a Neural Network - Which doesn't require such selection.

## The Naive Bayes Algorithm

The first model used the [Naive Bayes Algorithm](https://scikit-learn.org/stable/modules/naive_bayes.html) to train and test the data set.

It achieved a ~75% success at estimating survival rate.
![Image of Naive Bayes output](https://res.cloudinary.com/dxbk4zeyc/image/upload/v1622190548/GitHub%20Readme/NaiveBayes.png)

### Tools used
* Data from [OpenML.org](https://www.openml.org/d/40945)
* [pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [seaborn](https://seaborn.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* Algorithms from [scikitlearn](https://scikit-learn.org/)



## Using a Neural Network

Neural Networks are a form of deep learning wherein you don't need to know an ideal algorithm for your problem set ahead of time.

This particular Neural Network was run with only 3 layers distributed as:

5-5-1

For the last layer, it was used a [Sigmoid function](https://en.wikipedia.org/wiki/Sigmoid_function) to comprise the result within 0 and 1 (survived x not survived)

It achieved a ~80% success at estimating survival rate.
![Image of NN output](https://res.cloudinary.com/dxbk4zeyc/image/upload/v1622191522/GitHub%20Readme/NeuralNet.png)

### Tools used
* Data from [OpenML.org](https://www.openml.org/d/40945)
* [Keras](https://keras.io/)
* [TensorFlow](https://www.tensorflow.org/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.