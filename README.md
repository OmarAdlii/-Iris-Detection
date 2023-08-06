# Iris-Detection

1-Captures images from the webcam and saves them to the "data/images" directory.

2-Applies data augmentation techniques using the Albumentations library to create additional images for training a deep learning model for Iris Detection.

3-Loads images and corresponding labels (Key Points and classes) from the "aug_data" directory.

4-Builds a custom iris model using ResNet152V2 .

5-Compiles the custom iris detection model .

6-Trains the model using the loaded datasets.

7-Plots training and validation loss during the training process.

8-Runs real-time iris detection using the trained model on webcam feed and displays the webcam feed with detected iris.
