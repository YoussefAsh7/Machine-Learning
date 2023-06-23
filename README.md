# Cat and Dog Image Classifier
This code implements a binary image classification task to classify images of cats and dogs using a neural network. The code is written in Python and uses various libraries such as numpy, pandas, matplotlib, cv2, PIL, keras, and sklearn.

# Dataset
The dataset used in this code is the "30k-cats-and-dogs" dataset which contains 15,000 grayscale images of cats and 15,000 grayscale images of dogs, each of size 150x150. The dataset can be downloaded from Kaggle at the following link: https://www.kaggle.com/andrewmvd/30k-cats-and-dogs

# Code Structure
The code is structured as follows:

## Importing Libraries
In this section, the necessary libraries are imported for the code to run.

## Reading the Pictures
In this section, the images are loaded from the specified folders and preprocessed.

## Getting the Data Ready
In this section, the loaded images are split into training and testing sets and preprocessed further.

## NN Model (baseline model)
In this section, a baseline neural network model is defined, compiled, and trained on the data.

## CNN Model
In this section, a convolutional neural network (CNN) model is defined, compiled, and trained on the data.

## Testing
In this section, random images are selected, and both models predict whether they are cats or dogs.

# How to Run the Code
To run the code, follow these steps:

Download the "30k-cats-and-dogs" dataset from Kaggle.
Place the dataset in a folder called "Animal Images" in the root directory of the code.
Run the code in a Python environment with the necessary libraries installed.
# Conclusion
This code implements a binary image classification task to classify images of cats and dogs using a neural network. The code can be modified and extended to work with other datasets and image classification tasks.
