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
