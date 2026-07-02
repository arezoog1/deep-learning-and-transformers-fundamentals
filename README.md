# Fashion-MNIST Image Classification

This project explores multiple deep learning approaches for image classification using the Fashion-MNIST dataset.

The study compares traditional Multi-Layer Perceptrons (MLP), Convolutional Neural Networks (CNN), and modern attention-based representations while investigating the impact of data preprocessing and exploratory analysis.

## Objectives

* Perform exploratory data analysis on image data
* Build and train a Multi-Layer Perceptron (MLP)
* Build and train a Convolutional Neural Network (CNN)
* Compare performance across architectures
* Investigate attention mechanisms on image embeddings
* Analyze training behavior and generalization performance

## Dataset

Fashion-MNIST is a benchmark computer vision dataset containing grayscale images from 10 clothing categories:

* T-shirt / Top
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle Boot

Each image has a resolution of 28×28 pixels.

## Exploratory Data Analysis

The analysis includes:

* Class distribution
* Pixel intensity statistics
* Correlation analysis
* Sample visualization
* Noise inspection
* Feature extraction opportunities
* Data augmentation experiments

## Models

### Multi-Layer Perceptron (MLP)

* Multiple hidden layers
* ReLU activation
* Batch Normalization
* Dropout regularization

### Convolutional Neural Network (CNN)

* Convolutional layers
* Pooling layers
* Fully connected classifier
* Batch Normalization
* Dropout

### Transfer Learning

* ResNet-50 adaptation for Fashion-MNIST

## Training Pipeline

* Train / Validation / Test split
* Cross-model comparison
* Hyperparameter tuning
* Performance monitoring

## Evaluation

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Additional Study

A simplified attention mechanism is implemented to demonstrate how attention can highlight informative regions within image representations and improve feature aggregation.

## Technologies

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
