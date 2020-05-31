# Predictive-Maintenance-LSTM
In this notebook, we build an LSTM network for the data set and scenerio described at Predictive Maintenance Template to predict remaining useful life of aircraft engines. In summary, the template uses simulated aircraft sensor values to predict when an aircraft engine will fail in the future so that maintenance can be planned in advance.Describing the dataset
The dataset consists of sensor readings from a fleet of simulated aircraft gas turbine engines operating conditions as a multiple multivariate time series. The dataset consists of separate training and test sets. The testset is similar to the training set, except that each engine’s measurements are truncated some (unknown) amount of time before it fails. The data is provided as a ZIP-compressed text file with 26 columns of numbers. Each row represents a snapshot of data taken during a single operational cycle and each column represents a different variable.

I did this project as my Major Project. You can find the documentation too in the repository.

This project is also published in Kaggle with additional step by step information and comments.
https://www.kaggle.com/vamshikreddy/predictive-maintenance-using-lstm

Thanks to https://github.com/umbertogriffo/Predictive-Maintenance-using-LSTM for the code.
