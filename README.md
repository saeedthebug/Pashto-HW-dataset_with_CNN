# Handwritten Character and Digit Recognition using CNN Model

This project uses a Convolutional Neural Network (CNN) model to classify handwritten characters and digits. The dataset used in this project can be downloaded from Kaggle using the following link: https://www.kaggle.com/datasets/abdulbasitkh/pashto-isolated-alphabetss-and-numerals?datasetId=2025392

## Installation

To run this project, you need to install the following dependencies:

- TensorFlow
- Keras
- Pandas
- Numpy

You can install these dependencies using the following command:

```
pip install tensorflow keras pandas numpy
```

## Dataset

The dataset used in this project contains images of Pashto isolated alphabets and numerals. The dataset has been split into training and validation sets with 80% of the data used for training and 20% used for validation.

## Training

The CNN model used in this project was trained using the training set. The training accuracy of the model is 96% and the validation accuracy is 85%. The total error calculated for the model is 12%.
Usage

To use the model, you can load the saved model using the following code:

```
from keras.models import load_model

model = load_model('model.h5')
```
Once the model is loaded, you can use it to make predictions on new images.

## Conclusion

In conclusion, this project demonstrates the effectiveness of using a CNN model for recognizing handwritten characters and digits. With a training accuracy of 96% and a validation accuracy of 85%, the model is able to accurately classify new images with a low error rate of 12%.
