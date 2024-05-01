## Gradient Descent in Linear and Logistic Regression

Gradient descent is a powerful optimization algorithm widely used in the field of machine learning to minimize the cost function of a model. It is especially prevalent in both linear regression and logistic regression, which are foundational algorithms for predictive analytics.

### Linear Regression

In **linear regression**, the goal is to predict continuous values, such as prices or temperatures, by fitting a linear equation to observed data. The cost function often used in linear regression is the Mean Squared Error (MSE), which calculates the average of the squared differences between predicted and actual values. Gradient descent helps find the model parameters that minimize this MSE by iteratively adjusting the parameters in the direction that reduces the cost the most.

**Mathematical Update Rule**:
\[ \theta = \theta - \alpha \cdot \nabla_{\theta} MSE(\theta) \]
Here, \( \theta \) represents the coefficients, \( \alpha \) is the learning rate, and \( \nabla_{\theta} MSE(\theta) \) is the gradient of the MSE with respect to the coefficients.

### Logistic Regression

**Logistic regression** is used for binary classification tasks, such as predicting whether an email is spam or not spam. Unlike linear regression, logistic regression outputs probabilities by using the logistic (sigmoid) function, ensuring the output values are between 0 and 1. The cost function used in logistic regression is the binary cross-entropy or log-loss, which measures the performance of a classification model whose output is a probability value between 0 and 1.

**Mathematical Update Rule**:
\[ \theta = \theta - \alpha \cdot \nabla_{\theta} L(\theta) \]
Where \( L(\theta) \) represents the log-loss function, and \( \nabla_{\theta} L(\theta) \) is the gradient of the log-loss with respect to the coefficients.

