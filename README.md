# 🐶🐱 Pet Breed Classification using CNN (Oxford-IIIT Pets Dataset)

This project builds a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify dog and cat breeds from the Oxford-IIIT Pets dataset.

## 🚀 Overview

- Dataset: [Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/)
- Framework: TensorFlow + Keras
- Accuracy: ~96% Training, ~89% Validation
- Task: Image Classification of 37 Pet Breeds

## 🧠 Model Architecture

- Convolutional Layers
- MaxPooling
- Dropout
- Dense Layers
- Softmax Output for 37 Classes

## 🧪 Performance

- Trained for 10 epochs
- Real-world image prediction works well with unseen pet images

## 🖼️ Sample Predictions

Uploaded pet images (not from the dataset) were correctly classified as:

- 🐶 `great_pyrenees`
- 🐱 `Abyssinian`

## 📁 Files Included

- `oxford_pet_classifier.ipynb`: Full notebook
- `oxford_pet_model.keras`: Trained model
- `photo(cd).jpg`, `photo(cd2).jpg`: Prediction images

## 📌 How to Use

```python
# Load image and predict
predict_image('your_image.jpg')
