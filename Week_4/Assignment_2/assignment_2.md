# **Assignment 2**

## **ANN-1 Learning Rate**

1) Increasing blur blends the circles together while decreasing blur separates them. On the vanilla run, with a blur of 1, 85% of the runs achieved a model accuracy of at least 75% while varying the learning rate. With a blur of 2, the number drops to 82.5%. And with a blur of 0.5, the number drops further to 60%.

2) Determining if the mean value is a valid descriptor relies heavily on the distribution of the results. If it is normal/gaussian then there is not too much of an issue, but more often then not the results will not follow a normal distribution. The mean is very sensitive to the shape and skewness of the data, therefore the for the meta-experiment, it will not be valid in every case of the run.