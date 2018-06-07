# IEEE's Signal Processing Society - Camera Model Identification

The objective of this task was to identify which camera model was used using informations based on the image's noise.

# Description

The classification was carry out based on the image's noise, which was obtained by subtracting the original image by its filtered version. The features were extracted by a combination of wavelet based features and noise's texture characteristics using Local Binary Patterns. The dataset used is from the Kraggle competition: https://www.kaggle.com/c/sp-society-camera-model-identification.

![alt text](https://github.com/RenatoBMLR/Camera-Model-Identification/blob/master/figures/camara_images_transformations.png)

Two different models (Logistic Regression and Neural Network) were trained with different versions of images patches. Using an ensemble of these models we were able to have an accuracy of 0.86 in the validation set.


# Requirements

-   Python 3.6+

-   Numpy>=1.13.1+

-   Matplotlib>=2.0.2+

-   Scikit-learn>=0.19.1

-   SciPy>=0.13.3

-   PyWavelets>=0.4.0
