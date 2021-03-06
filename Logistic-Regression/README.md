Logistic Regression (Binary and Multiclass) in Detail:
https://ml-cheatsheet.readthedocs.io/en/latest/logistic_regression.html

Optimizer : {‘newton-cg’, ‘lbfgs’, ‘liblinear’, ‘sag’, ‘saga’},
default: ‘liblinear’ Algorithm to use in the optimization problem.

For small datasets, ‘liblinear’ is a good choice, whereas ‘sag’ and ‘saga’ are faster for large ones.
For multiclass problems, only ‘newton-cg’, ‘sag’, ‘saga’ and ‘lbfgs’ handle multinomial loss;

Loss(Cost) Function / Error: Function used to find the error at each step i.e. 
how much the predicted result is varying with the actual one. 
e.g. RMS, RAE, RSE, Cross Entropy - Binary, Categorical

Optimizer: Function used to decide the weight for the next step considering the loss function in order to reduce the error.
i.e. Goal- --> Minimize(Loss function)
e.g. SGD ( https://ml-cheatsheet.readthedocs.io/en/latest/gradient_descent.html ), RMSProp, AdaMax etc.

Learning Rate: The rate through which the optimizer is going to adjust the weight in order to achieve much loss in each step.
More learning rate is less time-consuming but will have impact on the training.


Activation Function:
[1] Threshold Function .  --- negative --> 0 && positive --> 1
[2] Sigmoid -- for all ---> between 0 and 1
[3] Rectifier . --> linear for positive and 0 for negative
[4] tanh -- for all ---> between -1 and 1
[5] Softmax . --> sum of all values will be 1
