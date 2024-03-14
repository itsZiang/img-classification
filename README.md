# Image Classification: Motorbike vs Bicycle

You can run the model directly at Google Colab: [https://colab.research.google.com/drive/1nKWE_BUnvmmFNEfDjCwGR9EODdLa1jsz?usp=sharing](https://colab.research.google.com/drive/1aybN7Riy5VH0vRG2FlU5USc8yk008veX?authuser=1#scrollTo=lAkCV_2UC4aR)
## Introduction

This repository contains code and resources for fine-tuning the VGG-19 model to classify images into two classes: motorbike and bicycle. The model is trained to distinguish between these two categories using transfer learning and fine-tuning on a custom dataset.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- Numpy version: 1.23.5
- TensorFlow version: 2.15.0
- OpenCV version: 4.8.0
- Matplotlib version: 3.7.1

## Usage

### Predicting Image Classes

To predict the class of an image using the pre-trained model, follow these steps:

1. **Open the Prediction Notebook:**
   - Open the `load_model.ipynb` notebook.

2. **Update Image Path:**
   - Inside the notebook, locate the cell containing the variable `image_path`.
   - Update the `image_path` variable with the full path to the image you want to classify.

3. **Run the Notebook:**
   - Execute the notebook cell by cell to make predictions.
   - The predicted class of the image will be displayed.
