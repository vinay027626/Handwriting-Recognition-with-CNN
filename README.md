# Deep Neural Network with Keras for MNIST handwritten classification and recognition
## Welcome to this end-to-end project that will include various design logics that are required to create stable training and evaluation deep neural network models !

We are going to employ the keras based python deep learning framework that readily offers complex mathematical layers that compute and form weights that are resultant of the data the model is viewing and learning from and then predict on new dataset.

Keras automates large amount of mathetmatical design that helps to rapidly develop and protype datasets and ML logic

keras basic nn

## Section O : Things to Know
Understand how to call in or import Keras-Based mathematical layers into your colab environment
Spend time on how a neural network is built and the logic to implement efficient and Optimal Training Networks for image classification
Explore the official documentation about the MNIST Dataset
Section D : Load the data in
Let's load in the dataset using Keras

```python
from keras.datasets import mnist 

(trainsetX, trainsety),(testsetX,testsety) = mnist.load_data()

print('Train: X = {}, y = {}'.format(trainsetX.shape, trainsety.shape)) 
print('Test: X = {}, y = {}'.format(testsetX.shape, testsety.shape))
```

## Section I.I : Initial Data Indagation
Start off by understanding what MNIST Data is in more detail
Note down the dimensions and other practical information about the MNIST dataset
Load in the dataset into your Colab Environment [Using Keras Datasets]
## Section I.II : Initial EDA
Explore the datasets descriptive statistics if needed
Create graphs of the counts of each class
Make deductions upon the class distribution
## Section II : Data Preparation
Normalize the pixel value of the all images
Why is scaling of the pixel value required ? Make a note
Explain the difference between pre-processed images and the normalized images
## Section III : Model Construction
What sort of Neural Network would you employ for this problem statement ?
Write down the skeleton flow of the model
Create a baseline model
Train the model
## Section IV : Model Evaluation
It is recommeded to to use Kfolds to evaluate your model, what other validation process could you employ ?
What would be the best value for K and why for this baseline model
Evaluate the model accordingly and make a note of it's performance with respect to it's accuracy

## Section V : Model Evaluation Metrics
Create Graphical plots of the model performance on the train and test set during individual folds
Is your model overfitting , underfitting or has the optimum fit ? Provide reasoning
Get the loss and validation loss of the model and also the accuracy and the validation accuracy
What are your inferences about the model performance ? Can you summarize your observations ?

## Section VI : Improving your models
What are some ways you can improve the performance of of your baseline model ?
Change some hyperparameters and observe the performance
Make note in the difference in performance between the baseline model and your improved model

## Section VII : Improve the depth
Add more convolutional layers to your baseline model
Increase the filter size of the conv layer as well
Add the pooling layers suitably
Compare the performance of the model with the baseline model
How much did the model improve?
What are the merits and demerits of increasing the depth of the model ?
Save the final model
