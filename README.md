# Transportation_Classifier

This project is a transportation classifier using the CIFAR-10 dataset. The dataset is divided into training, validation, and test sets. The model classifies images into different transportation categories.

# Dataset
The CIFAR-10 dataset is loaded using TensorFlow Datasets (TFDS) with the following splits:

Training Data: 100% of the training set
Validation Data: First 80% of the test set
Test Data: Remaining 20% of the test set

# Model
The model is a convolutional neural network (CNN) designed to classify images into transportation-related categories.

# Training
Preprocess the data using normalization
Compile the model with appropriate loss and optimizer.
Train the model using the training data and validate with the validation data.

# Evaluation
Evaluate the model using the test data to determine its accuracy and performance.
