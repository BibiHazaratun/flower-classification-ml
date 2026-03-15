# flower-classification-ml
Flower classification using CNN and MobileNetV2
# Flower Classification using CNN and MobileNetV2

## Project Overview
This project classifies flower images using deep learning models. Two models were implemented and compared:
- Convolutional Neural Network (CNN)
- MobileNetV2 (Transfer Learning)

## Dataset
The dataset contains multiple flower species images used for training and testing the models.Images are collect by clicking original flowers photos.

Structure:
dataset/
  train/
  test/

## Models Used
1. CNN
2. MobileNetV2

## Technologies
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Results
MobileNetV2 achieved better accuracy compared to the custom CNN model.

## How to Run

Clone the repository:

git clone https://github.com/BibiHazaratun/flower-classification-ml.git

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook
## Model Results

### CNN Accuracy
![CNN Accuracy](results/CNN_ACCURACY.jpeg)

### CNN Loss
![CNN Loss](results/CNN_LOSS.jpeg)

### MobileNetV2 Loss
![MobileNetV2 Loss](results/MobileNetV2_LOSS.jpeg)

### Confusion Matrix (CNN)
![Confusion Matrix CNN](results/Confusion_Cnn.jpeg)

### Confusion Matrix (MobileNetV2)
![Confusion Matrix MobileNetV2](results/Confusion_mobileNetV2.jpeg)

### Model Architecture
![CNN Model](results/CNN_Model.jpeg)

## Author
Bibi Hazaratun Nesa
