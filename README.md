# BrainTumourClassification

## Introduction

This project addresses the challenge of identifying and classifying brain tumours using applied machine learning techniques. It's no secret that brain tumours are worth our time - almost 90 percent of primary nervous system tumours are brain tumours [1]. The classes considered here are Glioma Tumour, Meningioma Tumour, Pituitary Tumour and of course the absence of a Tumour.

Efforts are made here to achieve two goals. First - the ability to identify if a particular MRI scan contains an tumour. Second - the ability to classify the tumour found within the classes previously mentioned.

## Repository Organisation

- *binary_classification* directory: Contains efforts towards the first task outlined above.
  - *SVM_SFT.ipynb*: An implemenation of the SIFT feature extraction framework, k-means clustering for unsupervised learning and a Support Vector Machine (SVM) binary classifier all working in alliance to indentify if a tumour exists in an MRI scan
- *SVM_SFT_saved_data* directory: Contains data saved from the execution of the SVM_SFT.ipynb file. Much of this data is laboriously generated. Therefore, it is pragmatic to store much of this data for later runs especially if it is deterministically generated. Note: this directory does *not* contain the file training_descriptors.py on GitHub as it exceeds the file size limit. It can be regenerated within the notebook though.
- *multiclass_classification* directory: Contains efforts towards the second task outlined above.
  - *SVM_SFT.ipynb*: A similar implementation to the SVM_SFT.ipynb file mentioned in the other directory except that it is applied to the multiclass classification problem.
  - *CNN.ipynb*: An implementaion of a convolution neural network aimed at classifying the MRI scans.
- *CNN_saved_data* directory: Contains sample data for some convolutional neural network models unsuccesfully trained.

## How to Get Started

To run code presented here, first you must ensure that your python environment meets the requirments outlined below. Secondly, the Jupyter notebooks can simply be opened and run provided that the IPython kernel can be connected to it. All of the file management in the notebook is relative and hence should be portable to wherever you decide to run the code.

## Dependencies

- [Python 3.9.X 64 Bit](https://www.python.org/downloads/release/python-399/)
- [Tensorflow 2.7.0](https://www.tensorflow.org/install)
- [Scikit-learn 1.0.1](https://scikit-learn.org/stable/)
- [Matplotlib 3.5.0](https://matplotlib.org/)
- [Numpy 1.21.4](https://numpy.org/)
- [OpenCV 4.5.4](https://opencv.org/)
- [IPython 7.30.1](https://ipython.org/)

## References

[1] S. Bhuvaji, A. Kadam, P. Bhumkar, S. Dedge, S. Kanchan, *Brain Tumor Classification (MRI)*, Kaggle (2020). [(Link)](https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri/metadata)