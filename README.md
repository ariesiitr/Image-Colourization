# Image-Colourization
Recruitment project for 1st year

### Overview:

  Deep Learning is an upcoming subset of machine learning which makes use of artificial neural
  networks. These are inspired by the human brain and its immense structure and function. Here we
  make use of it to colorize black and white images.
  
  
  ### Methodology
  
Taking input as a black and white image, this model tries to produce a colorized image. We are
using TensorFlow and Keras API. Our model is trained using Google Colab.

  1. To train the network, we start off with image datasets made up of colourful pictures. The
datasets used here are CIFAR10 and Landscape Dataset. Then we convert all images from
the RGB color space to the Lab color space. Just like RGB color space, Lab is an alternate
color space in which the three
channels represent:-
○ The L channel represents light
intensity only.
○ The a channel encodes
green-red color.
○ The b channel encodes
blue-yellow color
