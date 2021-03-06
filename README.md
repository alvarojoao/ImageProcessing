# ImageProcessing
Image Processing project for color constancy problem with Gaussian blur component


Installing Ipython Notebook
---------------------------

There are multiple ways of installing IPython. This page contains simplified installation instructions that should work for most users. Our official documentation contains more detailed instructions for manual installation targeted at advanced users and developers.


If you are looking for installation documentation for the notebook and/or `qtconsole`, those are now part of Jupyter.

### I already have Python

If you already have Python installed and are familiar with installing packages, you can get **IPython** with **pip**:

`pip install ipython`


### I am getting started with Python

For new users who want to install a full Python environment for scientific computing and data science, we suggest installing the Anaconda or Canopy Python distributions, which provide **Python**, **IPython** and **all** of its dependences as well as a complete set of open source packages for scientific computing and data science.

Download and install 

 1 - Continuum’s **Anaconda** <br/>
 2 - the free edition of **Enthought’s Canopy**.

Update IPython to the current version using the Terminal:

#### Anaconda:

`conda update conda` <br/>
`conda update ipython`

#### Enthought Canopy:

`enpkg ipython`


Important Imports:
------------------


		%matplotlib inline
		from __future__ import  division
		import matplotlib.pyplot as plt
		import numpy as np
		import math 
		import cv2
		from IPython.display import display, Image
		from scipy.ndimage import filters
		from scipy.spatial.distance import cdist,pdist,squareform
		from glob import glob
		import PIL

Make sure you have:

1 - [numpy](http://www.scipy.org/install.html#individual-binary-and-source-packages)<br/>
2 - [cv2](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_setup/py_setup_in_windows/py_setup_in_windows.html#installing-opencv-from-prebuilt-binaries)<br/>
3 - [scipy](http://www.scipy.org/install.html#individual-binary-and-source-packages) <br/>
4 - [PIL](http://www.pythonware.com/products/pil/)<br/>



Project
-------

In the file ["Experimentos Projeto de imagem.ipynb"](https://github.com/alvarojoao/ImageProcessing/blob/master/Experimentos%20Projeto%20de%20imagem.ipynb) you can see the algorithms and results of the article [Blur Robust And Color Constant Image Description](http://lear.inrialpes.fr/people/vandeweijer/papers/icip06.pdf).

The other files are just small templates of image processing filtering and transformations.
