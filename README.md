Handwritten Character Recognition using CNN

Project Overview
This project focuses on recognizing handwritten digits using Deep Learning and Computer Vision techniques. A Convolutional Neural Network (CNN) model is trained on the MNIST dataset to classify handwritten digits from 0 to 9.

Objective
The objective of this project is to build an AI model capable of identifying handwritten characters from image data.

Dataset
Dataset used: MNIST Dataset
MNIST contains:
* 60,000 training images
* 10,000 testing images
* Grayscale images of size 28×28 pixels
* Digits from 0 to 9

Technologies Used
* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab

Model Used
Convolutional Neural Network (CNN)

CNN layers used:
* Conv2D
* MaxPooling2D
* Flatten
* Dense Layers
* Softmax Output Layer

Project Workflow
1. Import required libraries
2. Load MNIST dataset
3. Normalize image pixels
4. Reshape data for CNN
5. Build CNN model
6. Train model
7. Evaluate model accuracy
8. Predict handwritten digits

Results
The model successfully classified handwritten digits with high accuracy.

Test Accuracy: (Add your accuracy here)

Example prediction:
Input Image → Handwritten Digit
Output → Correct Digit Prediction

Future Improvements

* Extend to alphabet recognition using EMNIST
* Build full word recognition using CRNN
* Deploy as a web/mobile app

Conclusion
This project demonstrates how Deep Learning can be used for handwritten character recognition. The CNN model achieved strong accuracy and successfully predicted handwritten digits from image inputs.
