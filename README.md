# Unet-2D-car-segmentation
This repository contains Jupyter and python implementation of U-net network for car segmentation in 2D based on grayscale or RGB color images. The training and test dataset are from carvana Kaggel challenge.

This implementation is based on Keras with Tensorflow backend. It has been tested on Python 3.6, Anaconda (4.7). The uplaoded code requires a GPU but if you do not have one, simply uninstall tensorflow-gpu (pip uninstall tensorflow-gpu), then install regular tensorflow (pip install tensorflow) and the code will work.


This can serve as an example for learning to:
  Train a network using your own images.
  Learn the structure of Unet netwrok.
  Test and fine tune a network to improve the segmentation task.
  Perform 2D segmentation with other datasets.

## Requirements

Create a virtual environment with Anaconda:  conda create -n DL_example python=3.6
Activate the environment: activate DL_example
Change directory to where you cloned the current files: cd ./where files are downloaded
Install required libraries: pip install requirements.txt

## Test
To test the notebook version, type the following in the command line:  jupyter notebook
This will open the notebook which will allow you to run either the grayscale (car_segmentation_Unet_grayscale.ipynb) or RGB (car_segmentation_Unet_rgb.ipynb) version of the code.

To test the python verion, 
  
