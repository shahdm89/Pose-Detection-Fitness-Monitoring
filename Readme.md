# Trash Image Classification
## This project aims to classify trash images into six categories: cardboard, glass, metal, paper, plastic, and trash. The dataset used for this classification task was collected from this repository.

## Overview
#### The code performs the following tasks:

1- Imports: Necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Keras are imported.
2- Reading Data: Data is read from the specified directory, and file paths along with their respective classes are stored in a DataFrame.
3- Exploring Data: The distribution of classes in the dataset is visualized using a count plot. Random images from each class are also displayed to understand the variety of shapes and sizes.
4- Cleaning Data: The dataset is split into training and testing sets, ensuring a balanced distribution of classes. Data resizing and augmentation techniques are applied to prepare the images for training.
5- Data Resizing and Augmentation: Images are resized to a suitable dimension and augmented via random transformations to prevent overfitting and generalize the model better.
6- Creating Model: A simple Convolutional Neural Network (CNN) model is created using Keras with layers for convolution, max-pooling, dropout, flattening, and dense connections.
7- Training: The model is trained on the augmented training data with specified configurations such as batch size, epochs, and validation data. Model checkpoints are saved for the best weights during training.
8- Evaluating: Model performance is evaluated using metrics such as accuracy, precision, recall, and F1 score. A confusion matrix is also plotted to visualize the performance across different classes.
### For detailed implementation and usage instructions, please refer to the code comments and documentation within the respective files.
