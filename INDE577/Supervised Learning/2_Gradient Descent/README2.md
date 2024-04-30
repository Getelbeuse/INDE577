Logistic Regression!

We use perceptron for binary classification tasks, but in those instances, the data was clearly linearly separable. What if it was the case that the data wasn't linearly separable, but instead had some overlap such that drawing a clear line through the data would be difficult? This is when we use logistic regression.

Logistic regression uses the sigmoid function to calculate a probability, which indicates the likelihood of a datapoint x being assigned to one label y or the other. Using the S-shaped curve, logistic regression maps data to a value between 0 and 1. 

Still, logistic regression has many similarities to its predecessors. It is a parameterized model with weight and bias inputs. It uses a variation of gradient descent (or it can use gradient ascent!). It is a single-neuron model and is a clever way to sort through nuanced data!

Read the notebook for a more detailed description of the algorithm as well as an analysis of the heart attack dataset.