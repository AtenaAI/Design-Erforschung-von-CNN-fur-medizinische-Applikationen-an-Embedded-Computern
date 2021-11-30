# Design-Erforschung-von-CNN-fur-medizinische-Applikationen-an-Embedded-Computern
Design Erforschung von Convolutional Neural Networks für medizinische Applikationen an Embedded Computern.

This repository contains the Jupyter Notebooks to create CNN models for Skincancer detection. These models are converted to TensorFlow Lite with float32 and int8. The models wiht int8 are compiled for the google Edge TPU for hardware acceleration on the embedded system.

For training, all the models use the Skincancer Dataset which is provided on Kaggle over this link:
https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign

In the folder "MassiveCNN Code", there are jupyter notebooks containing python code which create 3 Different types of CNN models that will be able to classify Skincancer with two classes (benign, malign).

The folder "Specific Purpose Code" contains code to test the models, to check the inference latency, and to convert the h5 models into TF Lite (float32 and int8).

The Folder "Int8 Modelle" contains a part of the models resulted from the code.

This work is part of my bachelor thesis in biomedical engineering at the Hochschule Bremerhaven in cooperation with the University Bremen.
