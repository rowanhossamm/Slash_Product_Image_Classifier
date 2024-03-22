# Slash_Product_Image_Classifier

This repository contains code for a product image classifier built using TensorFlow and Keras. The classifier is trained to recognize different categories of product images, including Accessories, Artifacts, Beauty, Fashion, Games, Home, Nutrition, Sports, and Stationary.

# Approach
The image classifier is implemented using a Convolutional Neural Network (CNN) architecture. Here's an overview of the approach:

Data Collection and Preprocessing: Product images are collected and organized into training and testing sets. Images are resized to a standard size of 150x150 pixels.

Model Architecture: The CNN model consists of convolutional layers followed by max-pooling layers to extract features from the images. The architecture also includes fully connected layers for classification.

Training: The model is trained using the training data, optimizing the model parameters using the Adam optimizer and minimizing the categorical cross-entropy loss function.

Evaluation: The trained model's performance is evaluated using the testing data, and metrics such as accuracy are computed to assess the model's effectiveness.

Prediction: Once trained, the model can predict the category of a given input image.

# Functionalities
The code in this repository provides the following functionalities:

Data Visualization: The plot_images function visualizes sample images from each category in the training data.

Data Augmentation: The training and testing data are augmented using the ImageDataGenerator to enhance model performance.

Model Building: The CNN model architecture is defined using Keras Sequential API, consisting of convolutional and fully connected layers.

Training: The model is compiled and trained using the training data.

Model Performance Plotting: The model's training and testing accuracy are plotted to visualize its performance over epochs.

Prediction: The predictions function takes a path to a test image and its actual label, preprocesses the image, makes predictions using the trained model, and visualizes the result.
