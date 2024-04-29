The goal of this project is to create the model that we will use as a target/victim in the attacks that we will carry out in Lab 2 in this course, "Untargeted Attacks on Your Classifier". We created a CNN-based deep learning classification model using traffic signs in this project. We used data augmentation to increase the prediction performance of the resulting model. The classification performance of the resulting model in the test dataset is approximately 99%.

The objective of this project is to complete a particular deep learning task: to classify traffic signs.
Completing the task of classifying traffic sign images requires many skills, tools, and types of knowledge, from building convolutional neural networks (CNNs) to assessing CNN model prediction performance.
This project is part of a series of labs, Adversarial Machine Learning. The other projects in this series are:

Traffic Sign Classifier (this lab)

Untargeted Attacks on Your Classifier

Targeted Attacks on Your Classifier

Adversarial Training

Defensive Distillation

Dataset

In this project, we will use a traffic sign dataset from the National Nature Science Foundation of China (NSFC). Please download the tsrd-train dataset and the tsrd-train annotation set. This dataset is about 150 MB.

Libraries and setup

You can use the Anaconda distribution of Python (3.8) and Conda for managing the libraries. The following Python libraries will be used in this project.

Keras: High-level deep learning framework
scikit-learn: Machine learning
cv2 (OpenCV): Image processing and general computer vision API
Matplotlib: General visualization
NumPy: Scientific computing
To install these libraries, download requirements.txt and run pip install -r ./requirements.txt. Any additional libraries you need can be installed with pip install “library” or conda install "library".
