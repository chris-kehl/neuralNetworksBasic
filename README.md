# neuralNetworksBasics
Basic beginners neural networks
This project uses the mnist data set to train a three layer neural network. The mnist data set contains handwritten numerals, the object is to detect accurately the written numerals in the testset.
My code allows for a 96% accuracy with a learning rate of 0.1 and epochs = 10.  

Keras_mnist scored a 97.06 on initial run

The data sets can be in the digital-recognizer competition, or the digital-recognition data set provided by Kaggle.  https://www.kaggle.com/c/digit-recognizer. the test file was uploaded, but the traning file is too large to load.  If you were to replicate this please download from Kaggle or a simular method.  Keras also has this dataset imbedded for a direct import.

The last few lines we've set the algorithm to attempt to recognize wild numbers that were captured with a cellphone from hand written images and a few images produced with Gimp.  The Gimp images did ok;however, the algorithm struggled with the photos form the cellphone.

In addition, a simple neural network for a baseball game predictions are used.  These came from a simple neural network book I am studying "Grokking Deep Learning" very simple and easy to follow. I am using Google Colab for these notebooks. We use numpy producing an easier version wih less code for our baseball game prediction.

dot_product_multiplication is code experimenting with simple dot product or matrix multiplication
