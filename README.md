
#Deep-Steganography-using-Autoencoders

In this project,the key idea is to create a model, that is, the architecture and weights that can transform any image into its corresponding latent space, a visually similar form of the image that occupies far less memory than the original. This latent space serves as an encrypted form of the image and can be transmitted to the other party via any public channel. On the other side, the user should have the decoder model for the corresponding encoder, which, in the case of this project, is symmetric and the exact opposite of the encoder model.

The methodology used in this project involves the implementation of an autoencoder via a convolutional neural network with the help of the keras and tensorflow libraries in python, to a large image dataset.

The entire process of training this model is done in the following steps:
 ####Importing the dataset####
  *Cleaning the data  	
	*Setting up the libraries
 	*Training the model using the conv2d, max pooling and upsampling functions
	*Create the corresponding decoder model.
  *Test against a subset of the dataset.

The algorithm/methods that we have used are:
 a) Conv2D:Conv2D basically applies a mask to a 2Dimage, as per concepts it is very similar to blurring in Computer Graphics. 
 b) MaxPooling2D: Aim of it is to downsample an input image or matrix, to reduce its dimentionality assumptions to be made about features to be contained in the sub-regions binned.
 c) UpSampling2D:  It is the process in which 0 valued samples are inserted between original samples to kind of increase the sampling rate. It adds spectral images to the real or rather original signal, which are based on multiples of original sampling rate.
