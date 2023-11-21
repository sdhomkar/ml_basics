# Hands-on Machine Learning (ML)

Siddharth Dhomkar, Department of Physics, IIT Madras

The purpose of this project is to provide a brief overview of machine learning strategies to solve relevant problems in physics. Python_basics contains useful information pertaining to the basics of programming, especially for novices, whereas, ML_basics is the main notebook that discusses an example problem of denoising via various methodologies.

The notebook allows the user to perform the following tasks:
1. Generate dummy training data
2. Split the data into training and testing tests
3. Construct various artificial deep neural network architectures - specifically - Dense, Long-short term memory, and convolutional neural network
4. Training the networks and testing the results

## Use of Google Colab platform
The code has ideally been designed to work in Colab. Specifically, the use of GPUs can significantly reduce the training times.

## Training data
The training and test data have been stored in .npz format. Arrays containing training data have been split into 2 portions to mitigate the file size constraints.

## Training histories and trained networks
The training histories have been stored as .csv files and entire pre-trained networks have also been saved.

## The problem under investigation

### Employing artificial neural networks for denoising noisy decoherence curves:

**Based on**:

* D.F. Wise, J.J.L. Morton, and S. Dhomkar, “Using deep learning to understand and mitigate the qubit noise environment”, PRX Quantum 2, 010316 (2021)
https://doi.org/10.1103/PRXQuantum.2.010316

* Fernando Meneses, David F. Wise, Daniela Pagliero, Pablo R. Zangara, Siddharth Dhomkar, and Carlos A. Meriles, "Toward Deep-Learning-Assisted Spectrally Resolved Imaging of Magnetic Noise", Physical Review Applied 18, 024004 (2022)
http://dx.doi.org/10.1103/PhysRevApplied.18.024004


Precise extraction of the nature of noise acting on a qubit underpins the optimization of dynamical decoupling protocols that can mitigate such noise. However, extracting accurate noise spectra from typical time-dynamics measurements on qubits is intractable using standard methods. The aforementioned articles propose a methodology to address this challenge using deep learning driven algorithms.

Although, the articles demonstrate a proof-of-principle technique to tackle problems related to precise noise spectroscopy, improved denoising methodology is required to handle incomplete and noisy experimental curves. Moreover, optimal smoothening of noisy data can assist in various applications. Thus, the aim of this notebook is to compare possible **Deep Learning Driven** strategies that can be utilized for this purpose.

