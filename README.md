# Model-Selection
When we have to solve a machine learning task: 
β’ there are diβ΅erent algorithms/classes
β’ algorithms have parameters
Question: how do we choose a algorithm or value of the parameters?


We are going to assume that  π¦=π(π₯)  with  π₯ββ  and  π¦ββ , where  π(π₯)  is some function. Then we are going to learn the polynomial of degree 2, 3, and 10 on 10 point of training data, and see how they perform on the training set. Then we will use a validation set of 10 points to pick the best model. At the end we will use 10 points as test set, to estimate the generalization error. You can think of having had 30 points in your data and decided to use 10 for training, 10 for validation, and 10 for testing.
