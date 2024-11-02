# Exploring 3D Sinusoidal Data using Artificial Neural Networks #


## Directions and Overview ##
The main purpose of this assignment is for you to gain experience using artificial neural networks to solve simple regression problems. In this assignment, you will fit a neural network to a noisy 3D sinusoidal data set. You will use a Sequential model that can be trained very quickly on the supplied data, so I want you to manually adjust hyperparameter values and observe their influence on the model's predictions. That is, you should manually sweep the hyperparameter space and try to hone in on the reasonable hyperparameter values, again, manually. (Yep, that means guess-and-check: pick some values, train the model, observe the prediction curve, repeat.)

So, play around and build some models. When you are done playing with hyperparameter values, you should finish by building an ANN that models the data reasonably well! You should be able to train a model and use it to predict a curve at least as good as mine, but your goal should be to obtain a smoother and less erratic curve.

(Side Note: Achieving a less erratic prediction curve could be done either by building a better model, OR by sorting the data more intelligently thereby plotting a prediction curve that looks better. I propose the ideal line is created by sorting the data in such a way that the resulting line minimizes the arc length of the curve. You don't need to worry about any of this, however you do need to generate a figure with a descent-looking prediction curve superimposed on the data.)

Here just just a few of the hyperparameters you can play around with:

number of nodes per layer
number of layers
activation functions
normalization method (should be negligible)
number of epochs
learning rate
loss function
You will know that you have obtained a reasonable model when the model's prediction curve looks reasonable. Below you will be asked to plot the model's prediction curve along with the training data. Even if you correctly train the model, you may find that your trendline looks totally crazy and out-of-this-world when you first plot it. If this happens to you, try plotting the model's predictions using a scatter plot rather than a connected line plot. You should be able to infer the problem and solution with plotting the trendline from examining this new scatter plot of the model's predictions. Your final submission, however, should contain a connected line plot.

Lastly in this assignment, you will compute the generalization error on the test set.
