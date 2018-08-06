# Camera Autofocus Model
A machine learning approach for defining contrast for autofocus.
## File Descriptions
* __autofocus_feedforward.ipynb__ is the file containing code for the feedforward autofocus neural network.
* __create_blur_dataset.ipynb__ is the file I used to create the unfocused image data from the focused images by blurring them with random filters.
* __vgg16_autofocus.ipynb__ is the file containing code for the cnn autofocus neural network using the convolutional layers and weights of the vgg16 model.  It also has the prediction code at the end for testing the 6 images in the test_blur folder which represent images at different camera lens positions.
* __autofocus_vgg16.h5__ is the keras model.
* __test_blur__ is the folder containing 6 images at different camera lens positions.
* __train_data__ contains training images (1400 total)
* __validation_data__ contains validation images (600 total)
## Steps to Run the program
#### 1. Download all files listed in this repo to a local directory.<br />
#### 2. Run .ipynb file for the type of model you want to create (cnn or feedforward).<br />
#### 3. For predictions, use the prediction code written at the end of the __vgg16_autofocus.ipynb__.<br />

