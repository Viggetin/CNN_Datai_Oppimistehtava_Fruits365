# CNN_Datai_Oppimistehtava_Fruits365

# CNN-based Fruit and Vegetable Image Classification

This project implements a Convolutional Neural Network (CNN) for classifying fruits and vegetables from images. The work was completed as part of the Data-AI course (Learning Assignment 2).

## Project Overview

The goal of this project was to explore CNN performance in image recognition tasks. The work started with a simple two-class classification problem (banana vs. cucumber) and was later extended to multiple fruit and vegetable classes.

## Technologies

- Python  
- TensorFlow / Keras  
- Convolutional Neural Networks  
- ImageDataGenerator  
- Matplotlib  
- Scikit-learn  

## Dataset

The project uses the Fruits-360 dataset from Kaggle:
- Approximately 120,000 images  
- 176 classes  
- Image resolution: 100×100 pixels  
- White background and controlled lighting  

## Results

- Banana vs. cucumber classification achieved near-perfect accuracy.
- Multi-class classification performance was significantly lower due to dataset imbalance.
- Best results were achieved with images having a white, shadow-free background.

## Limitations and Improvements

- Strong class imbalance affected model predictions.
- Real-world images reduced accuracy.

