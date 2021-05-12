
The training and testing data set can be loaded at line 36,37.

I pre-process the data with augmented one from line 42 to line 63

I have three versions of logistic_reg() functions:

1. logistic_reg(X,y): takes a data matrix and data label vector as input. limit tolerance is 10^-3 and learning rate = 10^-5. 
It takes a lot of time to converge, around 3 hours.

2. logistic_reg_modified(X,y,n): takes a data matrix , data label vector and maximum of number of iteration(n) as input . The learning rate is 10^-5.

3. logistic_reg_scaled(X,y,eta): takes a data matrix , data label vector and learning rate(eta) as input. The limit tolerance is 10^-6

4. find_test_error(X,y,w): takes data matrix , data label vector and weight vector as input and it returns the classification error.
 
 
Please let me know if there is anything I can do.

Thanks
Tasfia