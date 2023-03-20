# 77
Open Source Data Sharing
Create U-net for brain segmentation

The provided is a folder of T2 weighted axial brain slices with tissue labels.

Process:

(1)Build a bespoke Pytorch dataset for these examples. And to one hot encode the labels and convert to PyTorch tensors of the correct type and shape

(2)Create separate DataLoaders for train and validation sets create the Unet to segment this data

(3)try replacing the maxpools above with strided convolutions and the dropout and instead including a batchnorm

(4)train the network using the dice and cross entropy loss, report train and validation performance

(5)optimise the network to get the best performance
