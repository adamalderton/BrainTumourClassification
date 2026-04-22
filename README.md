# BrainTumourClassification

## Introduction

This project addresses the challenge of identifying and classifying brain tumours using applied machine learning techniques. It was completed as coursework for a graduate-level machine learning module at UCL. Brain tumours are a worthwhile area of study: almost 90 percent of primary nervous system tumours are brain tumours [1]. The classes considered here are Glioma Tumour, Meningioma Tumour, Pituitary Tumour and, of course, the absence of a tumour.

The work here is aimed at two goals. First, the ability to identify whether a particular MRI scan contains a tumour. Second, the ability to classify any detected tumour within the classes mentioned above.

## Repository Organisation

- *binary_classification*: Contains work towards the first task outlined above.
  - *SVM_SFT.ipynb*: An implementation of the SIFT feature extraction framework, k-means clustering for unsupervised learning and a Support Vector Machine (SVM) binary classifier, working together to identify whether a tumour exists in an MRI scan.
- *multiclass_classification*: Contains work towards the second task outlined above.
  - *SVM_SFT.ipynb*: A similar implementation to the *SVM_SFT.ipynb* file in the other directory, except applied to the multiclass classification problem.
  - *CNN.ipynb*: An implementation of a convolutional neural network aimed at classifying the MRI scans.


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
