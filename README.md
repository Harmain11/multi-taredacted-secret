# Multi-Task Gender and Age Prediction

## Overview  
This notebook demonstrates the development and implementation of a multi-task Convolutional Neural Network (CNN) model that simultaneously predicts age and gender from facial images. Using the diverse UTKFace dataset, the project highlights multitask learning capabilities for classification (gender) and regression (age) tasks with a shared CNN feature extractor.

## Features  
- Loads and preprocesses the UTKFace dataset of facial images with age and gender labels  
- Extracts image features suitable for CNN input  
- Implements a multi-output CNN with shared convolutional layers and separate branches for age regression and gender classification  
- Trains the model with appropriate loss functions and metrics for each task  
- Evaluates model performance with accuracy, R² score, classification report, and confusion matrix visualization  
- Visualizes training progress for loss and metrics using plots  

## Tech Stack  
- Python  
- Jupyter Notebook / Google Colab  
- TensorFlow / Keras for deep learning  
- Supporting libraries: numpy, pandas, matplotlib, seaborn, sklearn, PIL, OpenCV  

## How to Use  
1. Clone the repository or download the notebook.  
2. Upload the UTKFace dataset as described or adjust paths accordingly.  
3. Run the notebook cells sequentially to preprocess data, build, train, and evaluate the multi-task CNN model.  
4. Review generated plots, metrics, and saved model files.  

## Status  
This notebook is organized and formatted for clear presentation and reproducibility on GitHub.