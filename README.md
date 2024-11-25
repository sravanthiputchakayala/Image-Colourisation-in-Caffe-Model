

Image Colorization with Caffe

# Project Overview:

  This project demonstrates image colorization using a pre-trained Caffe model. The model takes a grayscale image as input and outputs a colorized version of the image.

# Prerequisites :

Python 3.x ,
OpenCV, 
NumPy, 
Caffe.


# Clone the Repository:
git clone " https://github.com/sravanthiputchakayala/Image-Colourisation-in-Caffe-Model.git "


# Install Dependencies:
pip install opencv-python numpy

Note: Ensure you have Caffe installed and configured correctly. 

# Usage:

Prepare your grayscale image: Ensure it's in a standard image format (e.g., JPG, PNG).
View the colorized image: The colorized image will be displayed in a window.

# How it Works:

Loading the Model: The Caffe model is loaded from the provided prototxt and caffemodel files.

Preprocessing the Image: The grayscale image is preprocessed by converting it to the LAB color space and normalizing it.

Forward Pass: The preprocessed image is fed into the Caffe model to generate the predicted 'ab' channels.

Colorization: The predicted 'ab' channels are combined with the original 'L' channel to form the colorized image.

Post-processing: The colorized image is converted back to the BGR color space and displayed.
