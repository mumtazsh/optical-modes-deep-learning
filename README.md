# Spatial Optical Mode Decomposition using Deep Learning

This is the companion code for the paper [Spatial optical mode decomposition using deep learning](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11511/115110M/Spatial-optical-mode-decomposition-using-deep-learning/10.1117/12.2568424.full?SSO=1).

In this paper, I have demonstrated using a convolutional neural network (CNN) architecture such as Resnet20 how to perform complete Laguerre-Gauss (LG) decomposition of an unknown, incoming laser beam using only intensity images.

The code is implemented in Keras/Tensorflow and the dataset is a simulated dataset with 100,000 optical beam images. The model is trained using GCP.
