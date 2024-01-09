# Scene Recognition CNN Model

## Overview

I have developed a Scene Recognition CNN model from scratch with the following layers: Convolution, MaxPooling, 2 Fully Connected layers. The first three layers use ReLU activation, and the last one uses softmax. The loss function is categorical cross-entropy. Stochastic gradient descent is employed for weight updates during backpropagation. The dataset used is a subset of the Kaggle scene recognition dataset, containing 3000 training images and 600 testing images, evenly distributed across three classes: Forest, Mountain, Building.

## Improvements

This model can be further enhanced by adding more layers to build a more powerful model capable of classifying a broader range of classes. Additionally, utilizing alternative SGD optimizers can lead to faster and more efficient convergence.

## Running the Model

Running the model takes about 1.5 hours approximately.
To run the model, follow these steps:

### Google Colab

1. Upload the provided Jupyter Notebook (IPYNB) to Google Colab.
2. Run the cells sequentially to observe the output.

### Local Execution

1. Ensure that Python 3 and a suitable IDE like PyCharm is installed
2. Ensure you have the required packages installed: numpy, requests, torchvision, Pillow, tensorflow, matplotlib, sklearn, math
3. Open the .ipynb notebook in the IDE, and run the cells sequentially, or click 'Run All'


