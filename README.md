

## Description
Hyperspectral Image (HSI) classification using Convolutional
Neural Networks (CNN) is widely found in the current
literature. Besides 3D-2D CNNs and
FuSENet, the other approaches do not consider both the spectral
and spatial features together for HSI classification task, thereby
resulting in poor performances. 3D CNNs are computationally
heavy and are not widely used, while 2D CNNs do not consider
multi-resolution processing of images, and only limits itself to
the spatial features. Even though 3D-2D CNNs try to model the
spectral and spatial features their performance seems limited
when applied over multiple dataset. In this article, a wavelet CNN, which is a variation of 2D CNN
for multi-resolution HSI classification. A wavelet CNN uses layers
of wavelet transform to bring out spectral features. Computing
a wavelet transform is lighter than computing 3D CNN. The
spectral features extracted are then connected to the 2D CNN
which bring out the spatial features, thereby creating a spatialspectral
feature vector for classification. Overall a better model
is achieved that can classify multi-resolution HSI data with
high accuracy. Experiments performed on
benchmark dataset, i.e. Indian Pines, University of Pavia, and
Salinas Scenes confirm the superiority of proposed SpectralNET
with respect to the state-of-the-art methods.


## Model

<img src="wavelet_cnn_0.5.png"/>

Fig: Proposed SpectralNet (Wavelet CNN) Model for hyperspectral image (HSI) classification.

## Prerequisites

- [Anaconda 4.8.3](https://www.anaconda.com/download/#linux)
- [Tensorflow 2.3.0](https://github.com/tensorflow/tensorflow/tree/r2.4)
- [Keras 2.4.3](https://github.com/fchollet/keras)

## Acknowledgement
https://github.com/gokriznastic/HybridSN  
https://github.com/menon92/WaveletCNN


