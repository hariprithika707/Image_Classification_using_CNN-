Classifying different classes in images with the help of deep knowledge

This code pattern demonstrates how images, specifically document images like buildings, forest, sea, glacier can be classified using Convolutional Neural Network (CNN).
##What is CNN and why CNN?##
A CNN is a supervised learning technique which needs both input data and target output data to be supplied. These are classified by using their labels in order to provide a learned model for future data analysis.

CNN has three main constituents - a Convolutional Layer, a Pooling Layer and a Fully connected Dense Network. The Convolutional layer takes the input image and applies m number of nxn filters to receive a feature map. The feature map is next fed into the max pool layer which is essentially used for dimensionality reduction, it picks only the best features from the feature map. Finally, all the features are flattened and sent as input to the fully connected dense neural network which learns the weights using backpropagation and provides the classification output.

The MOTIVATION behind the CNN is that it takes one section/window of the input image at a time for classification. Each time the CNN will produce a feature map for each section, in the convolutional layer. In the Pooling layer it removes the excess features and takes only the most important features for that section, thereby performing feature extraction.
Hence, with the use of CNNs we don't have to perform an additional feature extraction technique. CNNs require lesser pre-processing as compared to other similar classification algorithms.
