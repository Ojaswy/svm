# svm
The "Hello World" of Data Science:
  
    Iris Classification via Analysis of Measured Characteristics

This project is a brief and simple example of utilizing machine learning to predict Iris Flower classification by examining petal and sepal measurements.

The "Iris_descriptor.py" file is a simple script that creates some graphs to visualize the data set and then train a Support Vector Machine by importing and shuffling the data from "iris_data.csv", and feeding the first 80 samples into the algorithm as a training batch. Once the SVM has performed its training calculations, it is then given the last 20 data points of the previously shuffled data set to predict the flower classification. 

Because of the mature Support Vector Machine algorithms in Sklearn, and the relatively simple data set, prediction accuracy typically ranges between 90-100%.

******************************************************************************************************************************************

In addition to the iris_descriptor project, I have begun work on writing my own implementation of J.Platt's Sequential Minimal Optimization algorithm for training a Support Vector Machine. Rather than tackling the Quadratic Programming problem and handling the Lagrange multipliers of the Support Vector Machine in matrix form, this algorithm instead iterates over the array of multipliers, optimizing 2 at a time. 


-Stefan Soder-

******************************************************************************************************************************************
Relevant External Links:

Wikipedia page of the Iris Data Set:

    https://en.wikipedia.org/wiki/Iris_flower_data_set

Link to hosted sources files on University of California, Irvine servers:

    http://archive.ics.uci.edu/ml/machine-learning-databases/iris/
