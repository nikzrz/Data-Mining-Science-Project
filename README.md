# Data-Mining-Science-Project
Classify actions from the given dataset.
The given dataset is a collection of frames extracted from videos of people performing various exercises. These frames have been processed using MediaPipe's pose estimation framework, which detects the skeleton of the person in each frame and produces a set of 33 pose landmarks. The distances and angles between these landmarks have been calculated and included in the dataset.

The goal of the project is to use this dataset to train a machine learning model that can classify the action being performed in each frame. This can be accomplished using a variety of supervised learning algorithms, such as decision trees, support vector machines, or deep neural networks.

Once the model has been trained, it can be used to predict the action being performed in new frames by applying the same pose estimation process and feeding the resulting pose landmark data into the trained model. This can be useful for applications such as automated fitness tracking or monitoring of rehabilitation exercises.
