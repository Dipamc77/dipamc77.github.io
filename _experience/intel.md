---
title: "Intel"
collection: experience
type: "Machine Learning Engineer"
permalink: /experience/intel
---

Machine Learning Engineer at Intel since July 2018. Previously I was an intern at Intel from December 2017.

Fault Detection with deep unsupervised learning
----

This project aims to do defect detection for automotive parts without any labelled faults. My contributions are listed below

* Contributed to initial system developed for parts with single top view. The system uses a multiscale fully convolutional autoencoder for the parts. 
Training is done on only non-faulty parts. High reconstruction error on faultly is used to detect and localize faults.
* Extended the system to work on 3D parts with multiple camera views. 
* Improved the autoencoder system with PixelCNN autoregressive model and latent space autoregressive model. This allows use of density estimation as well as reconstruction error, 
achieving higher accuracy.
* Currently working on developing software for architecture search to work on data from different parts.

Classroom Action recognition
----

This project implements a system to provide classroom analytics. Action recognition is a part of the system. My contributions are listed below

* Integrated Denspose as backbone pose detector
* Contributed to dataset preparation for action recognition

CNN implementation on FPGA
----

This project implements a CNN model on an Intel Cyclone V for high speed object localization and optical character recognition. My contributions are listed below

* Optimized training and hyperparameters to reduce the size of CNN required for high speed optical character recognition while maintaining accuracy. 
* Implemented custom 8 bit layers for significant compute savings.
* Changed the architecture to use FPGA hardware friendly operations.
* Contributed to OpenCL FPGA implementation of CNN for high speed optical character recognition.