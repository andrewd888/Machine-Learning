# Handwritten Digit Classification Using BNN
The goal of this project is to build a image-classifier using Bayesian convolutional neural network to classifiy the MNIST handwritten digits. This will be a probablistic model, aiming to capture both __epistemic__ and __aleatoric__ uncertainty. 
We test the uncertainty quantifications using a smeared version of the dataset.

# The MNIST and MNIST-C datasets
The MNIST and MNIST-C datasets, which both consist of a training set of 60,000 handwritten digits with corresponding labels, and a test set of 10,000 images. The images have been normalised and centred. The MNIST-C dataset is a corrupted version of the MNIST dataset, to test out-of-distribution robustness of computer vision models.
<br>
The objective is to construct a neural network that classifies images of handwritten digits into one of 10 classes.

