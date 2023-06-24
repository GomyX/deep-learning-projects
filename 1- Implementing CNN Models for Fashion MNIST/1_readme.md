# Implementing CNN Models for Fashion MNIST
This project aims to implement and compare the performance of three different Convolutional Neural Network (CNN) models using Fashion MNIST dataset. The models will have varying numbers of filters in the first layer, starting with 64, 128, and 256 filters respectively. Additionally, the project will compare the performance of the first model when executed on both GPU and CPU.

## Dataset: Fashion MNIST
Fashion MNIST is a dataset containing 70,000 grayscale images of 10 different fashion categories, with 7,000 images per category. Each image is a 28x28-pixel square, representing an article of clothing at low resolution. The dataset is commonly used as a benchmark for image classification tasks.

## CNN Model Architectures
The project will implement three CNN models, each with a different number of filters in the first layer. The model architectures will be as follows:

* Model 1: Starting with 64 filters in the first layer.
* Model 2: Starting with 128 filters in the first layer.
* Model 3: Starting with 256 filters in the first layer.
Each model will consist of 2 or 3 convolutional and pooling layers, followed by fully connected layers and a softmax output layer for classification.

## Performance Comparison: GPU vs. CPU
The project will also compare the performance of Model 1 when executed on both GPU and CPU. This comparison aims to assess the impact of hardware acceleration on the training and inference time of the model. By running the same model on both GPU and CPU, we can evaluate the potential speedup and efficiency gains GPU computing provides for CNN tasks.
=> It took this model 9 mins to run on the GPU of Colab, and 32 mins to run on the CPU


## Implementation Details
The models will be implemented using a deep learning framework such as TensorFlow, which provides high-level APIs for building and training neural networks.

The implementation will involve the following steps:

## Data Preparation: Loading the Fashion MNIST dataset and performing any necessary preprocessing, such as normalization or data augmentation.
Model Construction: Defining the CNN architectures for the three models, specifying the number of layers, filter sizes, activation functions, and other hyperparameters.
Training: Training each model using the training set of Fashion MNIST, optimizing the model parameters using a suitable optimization algorithm (e.g. Adam).
Evaluation: Evaluate the trained models on the test set of Fashion MNIST to measure their classification performance, such as accuracy or loss.
Performance Comparison: Running Model 1 on both GPU and CPU to compare the execution time and potentially observe any performance improvements.
Analysis and Reporting: Analyzing the results, documenting the findings, and summarizing the performance comparison between the models and different hardware platforms.
## Requirements
To run the project, the following requirements must be met:
download the notebook and run it 

