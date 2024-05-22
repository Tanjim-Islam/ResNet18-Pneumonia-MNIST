# ResNet18-Pneumonia-MNIST

## Project Overview
In this project, I have implemented a ResNet18 model to classify pneumonia from chest X-ray images using the PneumoniaMNIST dataset from MedMNIST. The dataset is split into training, validation, and test sets, and the model is trained and evaluated on these sets to measure its performance.

## Install Requirements
To install the required libraries, use the following commands:
```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install medmnist
```

## Training and Validation Accuracy Metrics
Here are the accuracy metrics for the last epoch of training:
```
Epoch [30/30], Loss: 0.0159, Train Accuracy: 99.79%, Val Accuracy: 96.82%
```

## Test Accuracy
The accuracy of the model on the test images is: 85.90%