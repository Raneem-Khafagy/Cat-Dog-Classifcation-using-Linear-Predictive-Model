# Linear Predictive Model For Logistic Regression
the logistic model (or logit model) is used to model the probability of a certain class or event existing such as pass/fail, win/lose, alive/dead, or healthy/sick. This can be extended to model several classes of events such as determining whether an image contains a cat, dog, lion, etc. Each object is detected in the image would be assigned a probability between 0 and 1, with a sum of one. And this project is a **numpy** implementation of Logistic Regression and  [BACK-PROPAGATION](optimization)

## Loss function 
used **Logarithmic** loss function to measure how much the average model predictions vary from the correct values.

<p align="center">
The following graph shows the decay of loss function aginist the number of iterations 
  <img src="results\LossGraph.jpg" width="80%" title="Loss Graph">
</p>

## optimization
I used **Gradient Descent** an optimization algorithm, to update the parameters of our model
by iteratively moving in the direction of steepest descent as defined by the negative of the gradient.
## Sample of the Model output 
<p align="center">
  <img src="results\ModelSampleResults.jpg" width="80%" title="Model Sample Results">
</p>

## Model Accuracy 
<p align="center">
  <img src="results\ModelAccuracy.jpg" width="100%" alt="Model Accuracy">
</p>