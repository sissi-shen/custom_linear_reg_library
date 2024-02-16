I built my own library to train regression models using gradient descent. Specifically, I focused on building classes, similar to sklearn, that I could use to train the following three types of models:

• linear regression without regularization
• linear regression with L2 regularization
• logistic regression without regularization

To be able to train these models, I implemented these functions:

• loss function for linear regression
• loss function for ridge (linear) regression • loss function for logistic regression
• the derivative for each of the above