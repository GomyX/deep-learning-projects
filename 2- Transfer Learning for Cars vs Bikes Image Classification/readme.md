# Transfer Learning for Cars vs Bikes Image Classification
This repository contains a deep learning project that uses transfer learning to solve an image classification task on the Cars vs Bikes dataset. Transfer learning is a powerful technique that allows us to leverage pre-trained models and their learned features to solve similar tasks with limited labeled data.

## Dataset
The Cars vs Bikes dataset consists of a collection of labeled images, where each image belongs to one of two classes: "Car" or "Bike". The dataset is split into training and testing subsets, with a predefined distribution of samples in each class. The dataset is available for download at [link to dataset].

## Project Structure
The project is structured as follows:
**data**: This directory contains the training and testing data. The images are organized into separate folders for each class.

**models**: This directory contains the pre-trained ResNet-50 model, resnet50_model.h5, which will be used as the base model for transfer learning. You can either download a pre-trained ResNet-50 model or train your model and save it in this directory.

Getting Started
To get started with the project, follow these steps:

1. Clone this repository: git clone https://github.com/your-username/project-repo.git
2. Download the Cars vs Bikes dataset from the [link](https://www.kaggle.com/datasets/utkarshsaxenadn/car-vs-bike-classification-dataset).
3. Place the dataset into the data directory, following the structure mentioned earlier.
Optionally, download a pre-trained model and save it as pre-trained_model.h5 in the models' directory. Alternatively, you can train your model and save it using the provided notebook.
4. Open the image_classification.ipynb notebook in Jupyter Notebook or JupyterLab.
5. Follow the instructions in the notebook to train and evaluate the model using transfer learning.
6. Experiment with different hyperparameters, architectures, and techniques to improve the model's performance.
