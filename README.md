# MRI-Brain-Tumor-prediction-model
Deep Learning model predicting likeliness of brain tumor of a given image of an MRI scan of the brain. Trained with a dataset of 250+ MRI scans of the brain. 

This project uses a Convolutional Neural Network (CNN) with "Transfer Learning" (**MobileNetV2**) to classify scans as "Tumor Detected" or "Healthy." Because the dataset is small, I used Data Augmentation (rotating and flipping images) and Dropout layers to make sure the model actually learns patterns instead of just memorizing the pictures.

**Key Results:** The model achieves high accuracy by using pre-trained patterns a large set of other images. It provides a confidence percentage for every prediction and includes a randomized testing script to show real-world results visually.

Made using: Python (NumPy, Matplotlib, OpenCV & TensorFlow/Keras)
