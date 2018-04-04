# IEEE's Signal Processing Society - Camera Model Identification
![MKT](https://img.shields.io/badge/version-v0.1-blue.svg)
![MKT](https://img.shields.io/badge/language-Python-orange.svg)
![MKT](https://img.shields.io/badge/platform-Jupyter-lightgrey.svg)


# Description

The objective of this task is identifies which camera model captured an image by using traces intrinsically left in the image. The dataset used is from the Kraggle competition: https://www.kaggle.com/c/sp-society-camera-model-identification.

![alt text](https://github.com/RenatoBMLR/state-farm-distracted-driver-detection/blob/master/figures/data.png)

In this analysis we have made a comparasion between the classification performance obtained using tradicional approaches of Machine Learninig and some Deep Learning techniques.

# Requirements

-   Python 3.6+

-   Jupyter Notebook 5.0+

-   Numpy 1.13.1+

-   Matplotlib 2.0.2+

-   PyTorch 0.2.0_3 +


# Installation

This notebook was developed in [Jupyter Notebook](http://jupyter.org) using [Anaconda](https://anaconda.org) environment. This is not a requirement to run the notebook provided in this repository, however as it was used to develop it therefore it and it is a well known environment among data scientists is provided a quick guide in how to install and set up your environment.



## Anaconda

Go to [Anaconda](https://www.anaconda.com/download/#download) download web page and download the version best suited to your platform.

The Installation process is quite simple just follow the assistant that is provided when it is launched the application.

After the installation is done open a terminal and check the version installed using the following code via terminal :

```
$ conda -V

```
Then check for the packages using the following :

```
$ conda list

```
Check for the versions of listed on Requirements sessions and in case that is something out of data except for `Keras` that is not a default package use the following code via terminal.

```
$ conda update anaconda

```

## Pytorch

Go to the [pytorch](http://pytorch.org) web page and choose the version of the libraries installed on your system. It is important that they folllow the packages version described on Requriments section. 

After installing conda, use the following code via terminal.

```
$ conda install pytorch torchvision cuda80 -c soumith

```
