# BrainTumourClassification

## Introduction

This project addresses the challenge of identifying and classifying brain tumours using applied machine learning techniques. It's no secret that brain tumours are worth our time - almost 90 percent of primary nervous system tumours are brain tumours [1][(Link)](https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri/metadata). The classes considered here are Glioma Tumour, Meningioma Tumour, Pituitary Tumour and of course the absence of a Tumour.

Within this repository, efforts have been made to first discern whether an MRI brain scan displays a tumour using an implementation of the support vector machine (SVM) framework. A deep learning model was also leveraged to address this logistic regression problem. 

Next, a more complex deep learning model was used to not just perform identification (logistic regression) but to also perform classification (multiclass classification). With this, the transfer learning technique was also used to utilise pre-trained computer vision models. The base model with which the transfer learning was done was the **********

The performances of the models discussed are as follows:
- Identification:
  - SVM:
  - Deep Learning (CNN):
- Classification:
  - Deep Learning (CNN):
  - Deep Learning (CNN) with Transfer Learning:

## Repository Organisation

(Include the role of each file)

## Quick Start

(How to run your code)

## Dependencies

- [Python 3.9.X 64 Bit](https://www.python.org/downloads/release/python-399/)
- [Tensorflow 2.7.0](https://www.tensorflow.org/install)
- [Matplotlib 3.5.0](https://matplotlib.org/)
- [Numpy 1.21.4](https://numpy.org/)

## References

[1] S. Bhuvaji, A. Kadam, P. Bhumkar, S. Dedge, S. Kanchan, *Brain Tumor Classification (MRI)*, Kaggle (2020). [(Link)](https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri/metadata)