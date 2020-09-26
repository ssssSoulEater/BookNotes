课程基于 [Google ML Crash Cource](https://developers.google.com/machine-learning/crash-course)
# 1. 基本概念
* 监督学习(Supervise Machine Learning)
  * Lable
  * Feature
  * Example:
    * Labeled: For training
    * Unlabed: For Inference
* Model
  * Traning: creating or learning the model
  * Inference: applying the trained model to unlabeled examples
  * Type:
    * Regression: contious values
    * Classification: discrete values
* Linear Regression
  * Modle: y = wx + b
  * Loss: L = sum(y-y')^2 (usually use averageL=L/num, called Mean Square Error MSE)

* Training
  * Giving examples, trying to find a model that minimize the loss (empierical risk minimization)
