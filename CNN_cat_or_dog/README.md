Implemeted the CNN on dataset with intent to classifiy the dataset in 2 classes that are: cat or dog.

The Architecture created is: Conv. layer-> pooling layer-> Conv. layer-> pooling layer -> Flattening-> NN

Inside Pooling Lyaer Max Pooling is used to iintroduce the Spatial Invariance in our model ans also as it decreases the dimensionality and also at the same time extracts themost proiinent features from image
with stride of 1 Pixel.

The filter size in convolutional layer is taken as 3X3 with the stide of 2 to extract the miroscopic features form the Image.
