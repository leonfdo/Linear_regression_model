# Linear_regression_model
A fundamental statistical technique for simulating the relationship between a dependent variable and one or more independent variables is linear regression. It is frequently used to forecast or explain how the dependent variable will behave in light of the independent variables.

I learn PyTorch's fundamental syntax as well as the fundamentals of a basic machine learning model by coding this straightforward model.

* First step is to get a data set to train and test our model. For this I used points in range 0 to 1 with a step size of 0.02 as independent variable and the  points in the line  y=0.7*x+0.3 as dependent variables.	
* Then this dependent and independent  data is divided into two parts for training and testing purposes . 80% of the data for training and 20% of the data for testing.
* plotted  y vs x in a scatter plot diagram to visualize the data set.
  
  ![Screenshot 2023-08-29 012756](https://github.com/leonfdo/Linear_regression_model/assets/78163260/aad358f7-43ef-4aff-911c-97284750c81c)

* Then a simple model is created using one linear layer (because in the diagram we can see that there is a linear relationship between data).
* Then we need to select a relevant loss function and a optimizer for the given model. So for this regression model I selected to calculate the absolute difference as my loss function and SGD as my optimizer . For the optimizer a learning rate of 0.01 was given .
* Then the model was trained for 100 epochs and the loss function was displayed  and the predictions were calculated using the model for testing set.
  
![Screenshot 2023-08-29 012817](https://github.com/leonfdo/Linear_regression_model/assets/78163260/9de3dc63-9a6f-421c-94d9-677471c4cfe4)

![Screenshot 2023-08-29 012900](https://github.com/leonfdo/Linear_regression_model/assets/78163260/9144d454-c306-4e29-b1c0-5f70ca43cb51)
