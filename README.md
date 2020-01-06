# MNIST_fashion classifier
 a nn model which can classifiy between different fashion items.
 
 MNIST contains a dataset of many fashion items .
 our goal is to create a model to classify between each category ( 10 different classes).
 target acuracy is above 90%
 
 overview of the approach to solve this problem:
 
 1. download the dataset
 2. normalize the data and convert to tensor
 3. load the dataset into train set and test set (batch size = 64 containing 28*28 pixels)
 4. create model of i/p 784 tensor , few hidden layers , 10 tensors of o/p . ( since 64*28*28 = 784 1D vector, flatenning is done)
 5. train the model on trainning set( using dropout) , and evaluate at the test set.
 6. fine tune it by changing the learning rate , epochs, model architecture, dropout ...
  

