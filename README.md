# volcanic_eruption_detection_model
Introduction:
-This repository contains code for a volcanic eruption detection model built using TensorFlow, a popular deep learning framework. The model is designed to detect the presence 
 of volcanic eruptions in satellite imagery with a high degree of accuracy. The model uses a custom convolutional neural network to achieve an accuracy of 90% on the test 
 dataset.

# Dataset:
- The model was trained on a dataset of labeled satellite images. The dataset contains images of various sizes, resolutions, and levels of detail, with both positive and 
 negative examples of volcanic eruptions. The dataset used for this model cannot be shared due to licensing and confidentiality agreements.

# Model Architecture:
The model architecture consists of several convolutional layers with ReLU activation, followed by max-pooling layers to reduce the spatial dimensions of the feature maps. The final output of the model is a binary classification indicating whether or not a volcanic eruption is present in the input image.

# Training:
The model was trained using the Adam optimizer with a binary cross-entropy loss function. The model achieved an accuracy of 90% on the test dataset.
