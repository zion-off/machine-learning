# Image Classification using GoogLeNet

## Overview

This project focuses on implementing and training the GoogLeNet convolutional neural network architecture for image classification on the CIFAR-10 dataset. GoogLeNet, also known as Inception v1, is a deep learning model introduced by Google that achieves impressive performance while being computationally efficient. The project aims to demonstrate the effectiveness of this state-of-the-art architecture in accurately classifying images into different categories.

## Key Features

- **GoogLeNet Architecture**: Implementation of the GoogLeNet model, including the Inception module, which efficiently combines different convolutional filter sizes to extract rich features from the input images.
- **Inception Module with Dimension Reduction**: Custom implementation of the Inception module with dimension reduction, enabling efficient computation while maintaining representational power.
- **Data Preprocessing**: Utilization of PyTorch's built-in data transforms for image preprocessing, including random horizontal flipping, random rotation, and normalization.
- **CIFAR-10 Dataset**: Training and evaluation on the widely-used CIFAR-10 dataset, consisting of 60,000 32x32 color images across 10 different classes.
- **Training and Evaluation**: Comprehensive training and evaluation pipelines, including loss calculation, optimization, learning rate scheduling, and performance metric tracking.
- **Hyperparameter Tuning**: Ability to adjust hyperparameters such as learning rate, batch size, and number of epochs for optimal model performance.
- **Model Saving**: Automatic saving of the model with the best test accuracy during training.
- **Loss Curve Visualization**: Plotting of training and test loss curves for monitoring the model's convergence and generalization performance.

## Results

The GoogLeNet model achieved competitive performance on the CIFAR-10 dataset, showcasing its effectiveness in image classification tasks. The best testing accuracy obtained during the training process is reported, demonstrating the model's ability to accurately classify images across the 10 different classes.

## Usage

1. Ensure that the required Python packages (e.g., PyTorch, NumPy, Pillow, tqdm) are installed.
2. Prepare the CIFAR-10 dataset by running the provided code, which will download and preprocess the data.
3. Customize the hyperparameters (e.g., learning rate, batch size, number of epochs) as desired.
4. Run the training script, which will train the GoogLeNet model on the CIFAR-10 dataset.
5. Monitor the training progress and observe the loss curves for both training and testing.
6. Upon completion, the best model will be saved as `googlenet_best.pth`.
7. Evaluate the trained model on the test set to obtain the final testing accuracy.

## Conclusion

This project demonstrates the implementation and training of the GoogLeNet convolutional neural network architecture for image classification on the CIFAR-10 dataset. By leveraging the Inception module and efficient dimensionality reduction techniques, the model achieves competitive performance while maintaining computational efficiency. The provided code serves as a starting point for further exploration and experimentation with deep learning architectures for image classification tasks.