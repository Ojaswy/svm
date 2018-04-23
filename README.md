# svm
The "Hello World" of Data Science:
  
    Iris Classification via Analysis of Measured Characteristics

This project is a brief and simple example of utilizing machine learning to predict Iris Flower classification by examining petal and sepal measurements.

The "Iris_descriptor.py" file is a fully coherent classification script utilizing a Support Vector Machine to classify the flowers using a shuffled sampling of 80 examples from the "iris_data.csv" file. Once the SVM has performed its training calculations, it is then fed the last 20 data points of the previously shuffled data set to predict the flower classification. 

Unsurprisingly from the built in module and comparatively simple data set, the prediction is 100% accurate.

******************************************************************************************************************************************

In addition to the iris_descriptor project, I have begun work on writing my own implementation of J.Platt's Sequential Minimal Optimization algorithm for training a Support Vector Machine. Rather than tackling the Quadratic Programming problem and handling the Lagrange multipliers of the Support Vector Machine in matrix form, this algorithm instead iterates over the array of multipliers, optimizing 2 at a time. Please note that this script is WIP and will be continuously updated in the near future.


-Stefan Soder-

