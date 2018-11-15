Notes for Course:
## Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization

#### Regularization
 * In layman's terms: regularization artificially discourages complex or extreme explanations of the world even if they fit the what has been observed better. The idea is that such explanations are unlikely to generalize well to the future; they may happen to explain a few data points from the past well, but this may just be because of accidents of the sample.

 * Therefore, regularization is the kind of thing that discourages complexity, even if it means picking a less-accurate rule according to the training data.

 * A regression model that uses L1 regularization technique is called Lasso Regression and model which uses L2 is called Ridge Regression.

 * Dropout Regularization in NN refers to ignoring units (i.e. neurons) during the training phase of certain set of neurons which is chosen at random. By “ignoring”, I mean these units are not considered during a particular forward or backward pass.
