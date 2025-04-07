# Skillcraft-Technology-Internship
# Hand Gesture Recognition using Deep Learning

This project implements a deep learning-based hand gesture recognition system using PyTorch. It is designed to classify hand gestures from image data using a custom convolutional neural network.

## 📌 Features

- Image classification using a lightweight CNN.
- Dataset loading via `torchvision.datasets.ImageFolder`.
- Custom train-test split and mini-batch processing with `DataLoader`.
- GPU acceleration using CUDA (if available).
- Easily extensible architecture for deployment or further training.



- The model currently supports 5 gesture classes.
- Images are automatically converted to tensors using `ToTensor()` transformation.

## 🧠 Model Architecture

A simple CNN structure:
- `Conv2d` layer with 32 filters, kernel size 3
- `MaxPool2d` layer
- `ReLU` activation
- `LazyLinear` output layer with 5 units (gesture classes)

## 🏃‍♂️ Training

- Loss Function: `CrossEntropyLoss`
- Optimizer: `Adam`, learning rate = 0.001
- Epochs: 10
- Batch Size: 32


