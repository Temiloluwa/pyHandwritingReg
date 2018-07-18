# Description
My python implementation of the week3 exercise of the Machine Learning Course on Coursera by Andrew Ng.

## Libraries
- numpy - for array manipulations and algebraic opreations
- scipy - for cost function optimization and loading training data
- matplotlib - for training data visualization

## One vs all Logistic regression
This is an implementation of a one vs all logistic regression algorithm to classify gray scale image data sized 20 by 20 pixels into 10 classes. The data supplied contains 5000 training examples of handwritten digits (integers 0 to 9). It should be noted that the output training data y contains integer values between 1 and 10. The modulo function is utilized (digit % 10) to map the value of 10 to the appropriate value of 0.

Prediction results on the training data reveal an accuracy of 95.06%. Higher accuracy results are obtained by increasing the number of iterations for the optimization function.
